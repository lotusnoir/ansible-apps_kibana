# ansible-apps_kibana

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_kibana-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_kibana)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_kibana.svg)](https://github.com/lotusnoir/ansible-apps_kibana/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_kibana?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_kibana)
![Ansible Quality Score](https://img.shields.io/ansible/quality/)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Deploy kibana using ansible.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_kibana
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_kibana


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

