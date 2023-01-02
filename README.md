# Ansible Collection - jackson1719.lab

## Roles

**airvpn** - Installs Software for the VPN Provider AirVPN on Ubuntu
**tautulli** - Installs Tautulli Software on Ubuntu for Plex Monitoring
**ubuntu-motd** - Installs a custom MOTD on Ubuntu

## Example

### Install Collection
```
ansible-galaxy collection install jackson1719.lab
```

### Playbook Example
```
- name: Install Tautulli
  hosts: tautulli01
  become: yes
  roles:
    - role: jackson1719.lab.tautulli
```
