# Deveel OCM

The _Deveel OCM_ service is an experiemental (at today) _Communication-Platform-as-a-Service_ (CPaaS), providing a complex of services to enable _multi/omni-channel messaging_ capabilities in the applications integrating it.

## The Service Specifications

This repository provides a view of the specifications exposed by Deveel OCM services for common accessibility, such as _[OpenAPI](https://swagger.io/specification/)_.

Such specifications are produced into this repository during the CI/CD pipleine of the service, and they reflect only the versions in production

## The Repository Structure

The structure of the repository is providing a main point of access through the _specs_ subfolder, which contains child folders for each of the services: in there the specifications are listed by their orientation (_management plane_ or _data plane_) and their version.

## File Name Notation

The names of the specification files are composed by some fixed parts (such as the _name of the service_) and variable parts (such as the _version_ and _notes_).

The current notation of the version of the specifications implements the _Semantic Versioning_ (_SemVer_) model, that is progressive and structured in _major_ and _minor_ versions, prepended by a 'v' character (eg. _v1.1_ or _v2_): the version of the specifications reflects the one of the service they refer to.

An example structure would loook like

```
root/
|-- specs/
|   |-- channel/
|   |   |-- management/
|   |   |   |-- v1
|   |   |   |   |-- channel-v1.json
|   |   |   |-- v1.1
|   |   |   |   |-- channel-v1.1.json
|   |-- message/
|   |   |-- data/
|   |   |   |-- v1
|   |   |   |   |-- message-v1.json
```
