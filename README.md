# kong-payload-size-limiting | <sub><sup>A better request size limiting plugin for Kong</sup></sub>
[![version](http://img.shields.io/badge/version-v0.0.0-blue.svg)](#)  [![versioning](http://img.shields.io/badge/versioning-semver-blue.svg)](http://semver.org/) [![branching](http://img.shields.io/badge/branching-github%20flow-blue.svg)](https://guides.github.com/introduction/flow/)
[![license](http://img.shields.io/badge/license-apache-blue.svg)](LICENSE.md)

## Additional Features

* Set limit per `Content-Type` pattern

## Installation

Install the module one of the two following ways and then update the `custom_plugins` setting
within `kong.conf` or export the `KONG_CUSTOM_PLUGINS` environment variable. Finally, restart Kong.

### Via `luarocks install`:

```bash
$ luarocks install kong-payload-size-limiting
```

### Via `luarocks make`:

```bash
$ luarocks make kong-payload-size-limiting-*.rockspec
```
