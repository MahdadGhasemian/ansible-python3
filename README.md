# Ansible Role: Python3

Installs Python3 and PIP (along with pip modules: pyOpenSSL, docker, docker-compose, pymongo) for Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

```yaml
pyOpenSSL_python_module_version: "23.3.0"
docker_python_module_version: "6.1.3"
docker_compose_python_module_version: "1.29.2"
pymongo_python_module_version: "4.6.1"
```

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