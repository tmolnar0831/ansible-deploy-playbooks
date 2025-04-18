# System Deployment - Playbooks for Silent Operations

Deploy & configure Debian or RHEL virtual machines automatically.

## Group level variables

These variables should be in the group_vars:

```yaml
fqdn:      (string) FQDN of the machine
interface: (string) Main interface name
gateway:   (IP addres) Gateway IP address
user:      (string) Administrative user

packages:
  - (list) List of packages to install
```

## Host level variables -> host_vars/

```yaml
hostname: (string) Hostname of the machine
address:  (IP address) IP address of the machine
```

## License

MIT
