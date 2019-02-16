Jenkins Server
======================

Basic configuration to create a Jenkins Server.

## Install required roles.
`sudo ansible-galaxy install -r provisioning/requirements.yml --force`

## Prerequisites

- Copy custom.config.yml to config.yml and replace necessary values

## Running the playbook

- Copy hosts.example to hosts and edit it
- Run it with `ansible-playbook -i hosts provisioning/playbook.yml`
