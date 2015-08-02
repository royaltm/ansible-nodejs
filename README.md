NodeJS
======

Ansible role for installing nodejs from NodeSource RPMs

https://github.com/nodesource/distributions


Requirements
------------

Currently only for CentOS 6 & 7. Pull requests are welcome.


Role Variables
--------------

* `nodejs_version: 0.12.7` a supported nodejs version
* `nodejs_global_packages: [ ]` names of global npm packages to install

Example Playbook
----------------

    - hosts: example
      roles:
      - role: advertine.nodejs
        nodejs_version: "0.10.40"
        nodejs_global_packages:
          - jake
          - clean-css

License
-------

MIT

Author Information
------------------

Rafał Michalski

