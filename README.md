# Install Terraform

Ansible role to install the Terraform using APT for either Ubuntu 20.04 (focal), 22.04 (jammy), or 24.04 (noble).

Updated to handle ARM for the new Surface 7 Laptop.

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
