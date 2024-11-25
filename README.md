# Ansible Deploy Playbooks

Deploy Debian and RHEL machines in my KVM infrastructure.

## Group variables for the playbook

These variables can be in the group_vars:

```yaml
fqdn: FQDN of the machine
interface: Main interface name
gateway: Gateway IP address
user: Administrative user

packages:
  - List of packages to install
```

## Host variables for the playbook

These variables must be in the host_vars:

```yaml
hostname: Hostname of the machine
address: IP address of the machine
```