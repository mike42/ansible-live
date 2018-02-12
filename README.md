# Ansible live [![Build Status](https://travis-ci.org/mike42/ansible-live.svg?branch=master)](https://travis-ci.org/mike42/ansible-live)

This repository provides a demonstration and training environment for the Ansible
automatio tool, to be executed on an Ubuntu 16.04 or Debian 9+ control machine
with Ansible 2 or better.

You require Ansible and local `sudo` access to use the environment, as some extra
packages are added for LXC.

## Quick start

To begin, install Ansible and git, and clone this repository.

```bash
apt-get install ansible git
git clone https://github.com/mike42/ansible-live
cd ansible-live
```

Create the test machines:

```bash
./lab setup
```

You can then SSH to any of the test machines from meta/inventory.

eg.

```
ssh root@10.0.3.100
```

Destroy the test machines:

```bash
./lab teardown
```
