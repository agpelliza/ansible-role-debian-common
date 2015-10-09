# Ansible Role: Debian Common

An Ansible Role that upgrades and installs common packages for Debian Linux servers.

## Requirements

None.

## Role Variables

None.

## Example Playbook

    - hosts: all
      remote_user: vagrant
      roles:
        - debian-common
