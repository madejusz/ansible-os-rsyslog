Role Name
=========

Set logging central loggin file and enable logrotation for that file

Requirements
------------

N/A

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

- name: Rsyslog configation
  hosts: all
  #strategy: debug
  gather_facts: yes
  become: yes
  roles:
    - { role: ansible-os-rsyslog, tags: [ 'all' ] }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
