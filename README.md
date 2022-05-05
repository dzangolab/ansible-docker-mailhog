# Ansible Role: Install mailhog as a Docker container

An Ansible role to install [mailhog](https://github.com/mailhog/MailHog) as a Docker container.


## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
mailhog_hostname: mailhog
mailhog_network: mailhog
mailhog_image
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- dzangolab.docker_mailhog
```

## License

MIT

