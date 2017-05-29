# Ansible live [![Build Status](https://travis-ci.org/mike42/ansible-live.svg?branch=master)](https://travis-ci.org/mike42/ansible-live)

This repository provides a demonstration and training environment for the Ansible
automatio tool, to be executed on an Ubuntu 14.04 or Debian 8+ control machine
with Ansible 2 or better.

You require Ansible and local `sudo` access to use the environment, as some extra
packages are added for LXC.

## Quick start

To begin, install Ansible and git, and clone this repository.

```bash
apt-get install ansible git
git clone
cd ansible-live
```

Create the test machines:

```bash
./lab setup
```

Destroy the test machines:

```bash
./lab teardown
```
