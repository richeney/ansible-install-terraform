# Install Azure CLI

Ansible role to install the Terraform using APT for either Ubuntu 16.04 (xenial), 18.04 (bionic) or 20.04 (focal).

## Installation

`ansible-galaxy install richeney.install_terraform`

## Example Playbook

```yaml
- hosts: all
  roles:
    - richeney.install_terraform
```

## Requirements

None.

## Dependencies

None.
