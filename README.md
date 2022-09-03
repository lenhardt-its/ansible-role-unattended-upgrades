# Ansible Role: Unattended-Upgrades

[![ubuntu-18](https://img.shields.io/badge/ubuntu-18.x-orange?style=flat&logo=ubuntu)](https://ubuntu.com/)
[![ubuntu-20](https://img.shields.io/badge/ubuntu-20.x-orange?style=flat&logo=ubuntu)](https://ubuntu.com/)
[![debian-9](https://img.shields.io/badge/debian-9.x-orange?style=flat&logo=debian)](https://www.debian.org/)
[![debian-10](https://img.shields.io/badge/debian-10.x-orange?style=flat&logo=debian)](https://www.debian.org/)

[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg?style=flat)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/OnkelDom/ansible-role-unattended-upgrades?style=flat)](https://github.com/OnkelDom/ansible-role-unattended-upgrades/issues)
[![GitHub tag](https://img.shields.io/github/tag/OnkelDom/ansible-role-unattended-upgrades.svg?style=flat)](https://github.com/OnkelDom/ansible-role-unattended-upgrades/tags)
[![GitHub action](https://github.com/OnkelDom/ansible-role-unattended-upgrades/workflows/ansible-lint/badge.svg)](https://github.com/OnkelDom/ansible-role-unattended-upgrades)

## Description

Deploy and manage Unattended Upgrades for Ubuntu systems.

## Requirements

- Ansible >= 2.9 (It might work on previous versions, but we cannot guarantee it)

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file as well as in table below.

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `proxy_env` | {} | Proxy environment variables for Client|

## Example

### Playbook

```yaml
- hosts: all
  roles:
    - onkeldom.unattended-upgrades
```

## Contributing

See [contributor guideline](CONTRIBUTING.md).

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
