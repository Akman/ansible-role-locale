# Ansible Role: locale

Setup locale on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    locale: en_US.UTF-8

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - Akman.locale

*Inside `vars/main.yml`*:

    locale: ru_RU.UTF-8

## License

MIT / BSD

## Author Information

This role was created in 2017 by Alexander Kapitman
