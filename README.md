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

Defaults:

    locale: "en_US.UTF-8"
    project_directory: /rest/u/apps
    packages:
      - curl
      - vim
      - git
      - runit
      - htop
      - atop
      - imagemagick
      - python-pycurl
    users: []

Example:

    packages:
      - curl
      - vim
      - git
      - runit
      - htop
      - atop
      - python-pycurl
    users:
      - { name: git, home: /var/git, comment: "Common git user"}


Dependencies
------------

None

License
-------

MIT

Author Information
------------------

[Andrew Kumanyaev](http://github.com/zzet)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/zzet/ansible-common-role/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

