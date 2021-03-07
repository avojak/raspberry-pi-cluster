# Raspberry Pi K3s Cluster

## Packer

### Prerequisites

#### packer-builder-arm

Build packer-builder-arm:

```bash
$ git clone https://github.com/mkaczanowski/packer-builder-arm
$ cd packer-builder-arm
$ go mod download
$ go build
```

Install:

```bash
$ mkdir ~/.packer.d/plugins
$ cp packer-builder-arm ~/.packer.d/plugins
```

## Ansible

## K3s Dashboard

https://rancher.com/docs/k3s/latest/en/installation/kube-dashboard/