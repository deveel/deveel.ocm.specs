# Deveel OCM

The _Deveel OCM_ service is an experiemental (at today) _Communication-Platform-as-a-Service_ (CPaaS), providing a complex of services to enable _multi/omni-channel messaging_ capabilities in the applications integrating it.

## The Service Specifications

This repository provides a view of the specifications exposed by Deveel OCM services for common accessibility, such as _[OpenAPI](https://swagger.io/specification/)_.

Such specifications are produced into this repository during the CI/CD pipleine of the service, and they reflect only the versions in production

## The Repository Structure

The structure of the repository is providing a main point of access through the _specs_ subfolder, which contains child folders for each of the services: in there the specifications are listed by their orientation (_management plane_ or _data plane_) and their version.

An example structure would loook like

```
root/
|-- specs/
|   |-- channel/
|   |   |-- management/
|   |   |   |-- v1
|   |   |   |-- v1.1
|   |-- message/
|   |   |-- data/
|   |   |   |-- v1 
```
