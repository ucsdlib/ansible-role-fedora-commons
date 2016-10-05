Fedora Commons
==============

Installs Fedora Commons jetty console

Requirements
------------

Requires ucsdlib.java role, and Ansible 1.9+.

Role Variables
--------------

* `fedora_commons_version` Version to install
* `fedora_commons_webproxy` (optional) Proxy variables
* `fedora_commons_install` Location to install to

Dependencies
------------

Requires java, provided by `ucsdlib.java`.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ucsdlib.fedora-commons, fedora_commons_version: 4.6.0 }

License
-------

BSD 2 Clause

Author Information
------------------

John H. Robinson, IV  
The Library  
UC San Diego  
