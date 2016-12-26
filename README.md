## Ansible-Grafana
> an ansible role to install, configure and manage [Grafana](http://grafana.org/)

[![xuqingfeng.grafana](https://img.shields.io/badge/role-xuqingfeng.grafana-blue.svg?style=flat-square)](https://galaxy.ansible.com/xuqingfeng/grafana/)

### Installation

`ansible-galaxy install xuqingfeng.grafana -p roles`

### Role Variables

```yaml
# vars/main.yml
grafana_package_url: https://grafanarel.s3.amazonaws.com/builds/grafana-4.0.2-1481203731.x86_64.rpm # for version 4.0.2; get from http://grafana.org/download/

# default/main.yml
# ...
```

### Example Playbook

```yaml
- hosts: server
  roles:
    - xuqingfeng.grafana
```

### Docker

[https://github.com/grafana/grafana-docker](https://github.com/grafana/grafana-docker)