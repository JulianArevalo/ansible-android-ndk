android-ndk
=========

Ansible role to install the Android NDK.

Requirements
------------

Ubuntu 14.04
Ubuntu 16.04
MacOSX 10.12

Role Variables
--------------

tools_path: ~/tools
android_ndk_cfg: Android NDK version to download and install.

Dependencies
------------

geerlingguy.homebrew

Example Playbook
----------------

Here a playbook example to install the Android NDK

    - hosts: all
      roles:
         - role: JulianArevalo.android-ndk
           tools_path: "~/tools"
           android_ndk_cfg:
             version: 15c

License
-------

MIT
