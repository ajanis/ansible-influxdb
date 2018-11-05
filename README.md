InfluxDB
========

An Ansible role to install, configure, and manage
[InfluxDB](https://github.com/influxdata/influxdb) (a time-series
database).

Requirements
------------

Prior knowledge/experience with InfluxDB is highly recommended. Full
documentation is available
[here](https://docs.influxdata.com/influxdb/latest).

Installation
------------

Clone repository to your ansible roles folder

Role Variables
--------------

The high-level variables are stored in the `defaults/main.yml` file. The most important one being:

```
# Channel of InfluxDB to install (stable, unstable, nightly)
influxdb_install_version: stable
```

More advanced configuration options are also stored in the
`defaults/main.yml` file, which includes all of the necessary bells
and whistles to tweak your configuration. There are more advanced
runtime options available in the `vars/main.yml` file as well.


Dependencies
------------

No other Ansible dependencies are required. This role was tested and
developed with Ansible 1.9.4.

