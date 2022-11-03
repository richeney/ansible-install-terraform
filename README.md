# Install Terraform

Ansible role to install the Terraform using APT for either Ubuntu 16.04 (xenial), 18.04 (bionic) or 20.04 (focal).

Based on the Linux | Ubuntu/Debian tab within <https://www.terraform.io/downloads>.

## Installation

`ansible-galaxy install richeney.ansible-install-terraform`

## Example Playbook

```yaml
- hosts: all
  roles:
    - richeney.ansible-install-terraform
```

## Requirements

None.

## Dependencies

None.
