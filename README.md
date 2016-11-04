## Ansible-Grafana
> an ansible role to install, configure and manage [Grafana](http://grafana.org/)

[![xuqingfeng.grafana](https://img.shields.io/badge/role-xuqingfeng.grafana-blue.svg?style=flat-square)](https://galaxy.ansible.com/xuqingfeng/grafana/)

### Installation

`ansible-galaxy install xuqingfeng.grafana -p roles`

### Role Variables

```yaml
# vars/main.yml
grafana_version: 3.1.1 # grafana version number

# default/main.yml
# ...
```

### Dependencies

### Example Playbook

```yaml
- hosts: server
  roles:
    - xuqingfeng.grafana
```