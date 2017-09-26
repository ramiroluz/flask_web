Role Name
=========

Installs Flask 

Requirements
------------

None

Dependencies
------------

None 

Example Playbook
----------------

Here's how to use role:

---
- name: provision debian 8 (jessie) droplets 
  hosts: all
  gather_facts: yes
  roles:
      - name: ramiroluz.flask_web
        become : yes


License
-------

BSD

Author Information
------------------

John Olson (Original https://github.com/inthebackofmymind/flask_web)
Ramiro Batista da Luz
