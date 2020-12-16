# Xen scripts

## Description

This repository contains the scripts used to generate a VM architecture on a Xen server
using only a `xml` file as input.

The VMs will be generated,
configured using a custom iso,
auto started at reboot,
and a Ansible groups vars folder will be created.

## Usage

### Add this repo to the PATH variable

```sh
export PATH="$PATH:/path/to/this/repo/"
```

### Generate the VMs

```sh
generate-topology /path/to/topology.xml
```
