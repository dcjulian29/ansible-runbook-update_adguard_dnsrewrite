# Ansible Runbook: update_adguard_dnsrewrite

[![Build](https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite/actions/workflows/build.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite/actions/workflows/build.yml) [![Release](https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite/actions/workflows/release.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite/actions/workflows/release.yml) [![GitHub Release](https://img.shields.io/github/v/release/dcjulian29/ansible-runbook-update_adguard_dnsrewrite)](https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite/releases) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-runbook-update_adguard_dnsrewrite.svg)](https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite/issues)

This is an Ansible runbook that will update AdGuard DNS rewrite configuration and restart.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
collections:
- name: dcjulian29.update_adguard_dnsrewrite
  type: git
  source: https://github.com/dcjulian29/ansible-runbook-update_adguard_dnsrewrite.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy collection install -r requirements.yml
```

To excute the runbook:

```shell
ansible-playbook dcjulian29.update_adguard_dnsrewrite.runbook.yml
```
