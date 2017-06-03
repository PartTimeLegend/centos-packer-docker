# CentOS Packer Docker

Ever need to fire up a CentOS Docker host really quickly? Look no further.

## Depends on:
* [Packer](https://www.packer.io)
* [AWS](https://aws.amazon.com)

### Usage

Validate template.
`packer validate packer-centos-docker.json`

Build
`packer build packer-centos-docker.json`
