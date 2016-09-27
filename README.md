# payload-size-limiting | <sub><sup>A better payload size limiter plugin for Kong</sup></sub>
[![version](http://img.shields.io/badge/version-v0.0.0-blue.svg)](#)  [![versioning](http://img.shields.io/badge/versioning-semver-blue.svg)](http://semver.org/) [![branching](http://img.shields.io/badge/branching-github%20flow-blue.svg)](https://guides.github.com/introduction/flow/)

The payload-size-limiting plugin has additional features over the stock response-size-limiting
plugin that comes with Kong, which includes:

* Ability to limit by `Content-Type` pattern (i.e. have a different limit for JSON and file
  uploads)
* TODO: Ability to ignore `Content-Length` header in responses to catch abusive clients
