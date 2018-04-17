Docker Registry
===============


Requirements
------------


Role Variables
--------------


Dependencies
------------

At the moment the installation of `docker-python` has not been added.
If the script fails, please perform the installation with:

```
$ yum install -y docker-python
```


Example Playbook
----------------

```
- name: Deploy docker registry
  hosts: localhost
  roles:
    - armandk.docker-registry
```


Author
-------
Armand Komenan