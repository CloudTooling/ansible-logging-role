# ansible-logging-role
[![Build](https://github.com/CloudTooling/ansible-role-logging/actions/workflows/workflow.yml/badge.svg)](https://github.com/CloudTooling/ansible-role-logging/actions/workflows/workflow.yml)
[![Ansible Role](https://img.shields.io/ansible/role/d/cloudtooling/logging)](https://galaxy.ansible.com/ui/standalone/roles/cloudtooling/logging/)

Easy deployment of logging app on Linux

## Usage

Create a *requirements.yml* refering to this role and a *playbook.yml*, e.g.:
```

  roles:
    - role: logging
      journal_cleanup_max_age: 14days
```
