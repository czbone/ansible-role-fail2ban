Fail2Ban Setup with Ansible
===========================

This Ansible Role installs, configures and updates fail2ban for a linux server.

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------

Variables are self speaking or documented in:   
* `defaults/main.yml`

Dependencies
------------

This Ansilbe Role has no dependencies.

How to use
------------

##### Download zip and unarchive it at `roles` directory in your Ansible project

```yml
# main.yml
roles:
  - ansible-role-fail2ban
```

##### Ondemand install at launch Ansible

```yml
# requirements.yml
- src: https://github.com/czbone/ansible-role-fail2ban
  name: fail2ban
```

```yml
# main.yml
roles:
  - fail2ban
```


