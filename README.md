# Role Name
=========

Ansible role to set up Docker environment on Ubuntu.


# Role Variables
--------------

**hstname** - The hostname of the server. 

# Running the role
---------------

    - hosts: servers
      roles: 
        - Docker-Conf
      vars:
        hstname: myserver

# License
-------

BSD


# Author Information
------------------

Raman Sailopal
