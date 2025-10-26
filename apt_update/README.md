# Rolle: apt_safe_upgrade

Sicheres apt update + upgrade mit Backup und Diff neuer Konfigurationsdateien.

## Nutzung
```yaml
- hosts: LinuxUbuntu
  become: true
  roles:
    - apt_safe_upgrade
```
