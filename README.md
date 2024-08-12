# CoreDNS

This repository contains Monk.io template to deploy CoreDNS server

## Prerequisites

- [Install Monk](https://docs.monk.io/basics/monk-in-10)
- Register and Login Monk
- Add Cloud Provider
- Add Instance

## Make sure monkd is running

```bash
$ monk status
```

## Clone Repository

```bash
git clone https://github.com/monk-io/monk-coredns
```

## Load Template

```bash
cd monk-coredns
monk load MANIFEST
```

## Deploy

```bash
$ monk run coredns/coredns
```

## Stop, remove and clean up workloads and templates

```bash
monk purge coredns/coredns
```
