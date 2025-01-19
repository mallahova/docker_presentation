# What is a container?

A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application.


### Containers

Containers are similar to virtual machines in that they provide an isolated environment for installing and configuring binaries/libraries, but rather than virtualizing at the hardware layer containers use native linux features (cgroups + namespaces) to provide that isolation while still sharing the same kernel.

![](./readme-assets/container.jpg)

This approach results in containers being more "lightweight" than virtual machines, but not providing the same level of isolation:

- No dependency conflicts
- Even better utilization efficiency
- Small blast radius
- Even faster startup and shutdown (seconds)
- Even faster provisioning & decommissioning (seconds)
- Lightweight enough to use in development!


