# Ansible Role: PHP

Forked role from Geerlingguy Ansible Role PHP (https://github.com/geerlingguy/ansible-role-php). It's only compatible with Debian (Maybe Ubuntu, but not tested.)

This role installs PHP 7.1 from the sury.org package repo and configure it to work with latest MySQL, Redis (with phpredis and session.save_handler) and nginx as webserver.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-role-debian-php-7.2
```

## License

MIT / BSD

