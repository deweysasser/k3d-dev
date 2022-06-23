k3d-cev
=======

Automation/support for setting up a local k3d-dev cluster, with local registry, for building and
testing containers against a local kubernetes cluster.


Usage
=====

To create a development registry and cluster, run:

`./setup-local-dev`

To destroy both, run

`./destroy-local-dev`

Dependencies
============

* Rancher's k3d` (https://k3d.io/)
* A local Docker (https://www.docker.com/)
* BSD compliant `sed` and `nc`

Platforms
=========

This has been tested on MacOS 12.4. It should substantially work on other platforms but has yet to
be tested.