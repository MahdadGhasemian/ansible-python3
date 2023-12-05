# Ansible Role: Python3

Installs Python3 and PIP (along with pip modules: pyOpenSSL, docker, docker-compose, pymongo) for Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook (using default package)

    - hosts: servers
      roles:
        - role: MahdadGhasemian.ansible-python3
          become: yes

## License

MIT / BSD

## Author Information

This role was created in 2023 by [Mahdad Ghasemian](https://mahdad.me/).