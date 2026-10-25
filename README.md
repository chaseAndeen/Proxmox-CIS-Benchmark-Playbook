# Proxmox CIS Benchmark

Ansible Playbook for implementing the Debian 13 CIS benchmark.


## CIS 1.1.1.1-8

### Usage:

Executing a read-only audit:
```
ansible-playbook -i inventory.yaml audit.yaml
```

Executing an audit with automatic remediation:
```
ansible-playbook -i inventory.yaml remediate.yaml
```

---
pve9 adaptation reference:

 https://github.com/HomeSecExplorer/Proxmox-Hardening-Guide/blob/main/docs/pve9-hardening-guide.md