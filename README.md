Role Name
========

With this role you can prepare you machine to work with setup:
 - curl
 - vim
 - git
 - runit
 - htop
 - atop
 - imagemagick
 - python-pycurl

System encoding to UTF-8
Adding google ns to resolf.conf
Prepare project directory

Requirements
------------

None

Role Variables
--------------

  locale = "en_US.UTF-8"
  project_directory = /rest/u/apps
  packages:
    - curl
    - vim
    - git
    - runit
    - htop
    - atop
    - imagemagick
    - python-pycurl

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

License
-------

MIT

Author Information
------------------

Andrew Kumanyaev
http://github.com/zzet
