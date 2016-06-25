Jenkins Server
======================

Basic configuration to create a Jenkins Server.

## Install required roles.
`sudo ansible-galaxy install -r provisioning/requirements.yml --force`

## Prerequisites

- Copy custom.config.yml to config.yml and replace necessary values

## Start the VM
`vagrant up`

## Start the DigitalOcean server
`vagrant up --provider=digitalocean`
