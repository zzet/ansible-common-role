Role Name
========

With this role you can prepare you machine to work with:

  Setup system encoding to UTF-8

  Setup predefined packages

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
