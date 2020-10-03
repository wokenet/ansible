# Woke Ansible Runbooks

This repository contains the ansible runbooks we use to manage and configure
our servers. Our goal is to make it possible to replicate our systems.

These ansible tasks assume a base system of Ubuntu 20.04.

Currently, this consists of configuration for creating a remote
[Streamwall](https://github.com/chromakode/streamwall) stream server. This
requires pretty beefy dedicated hardware -- currently we're running on a system
with a Ryzen 3900X and an NVIDIA RTX 4000.


# TODOs

* Disable power management
* Fix streamwall not starting on boot.
* Add more netdata things.
* Fix netdata cloud enrollment.
