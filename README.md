# PerconaLive 2014 - MariaDB multi-source replication

----

## Requirements

The requirements for running this vagrantfile are:

- VirtualBox 4.3.18 for guest additions
- Vagrant 1.5+

----

## Installation

Download via git command; or download compressed file and cd to correct directory

```
  git clone https://github.com/dtest/pluk14-mariadb
  cd pluk14-mariadb
  vagrant up
```

----

## Usage

The Vagrantfile sets up a single box with 1GB memory. There will be 4 mariadb instances running, but the memory limit can be modified if required.

```
  cd /path/to/pluk14-mariadb
  vagrant up
  vagrant ssh
```
