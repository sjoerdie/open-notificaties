# Single-server deployment

The [official documentation][docs] documents the installation procedure of Open
Notificaties. If you're looking to install Open Notificaties, please follow that
documentation.

## For maintainers, power-users and devops engineers

This directory contains example [Ansible][Ansible] playbooks to deploy Open Notificaties.

The playbooks are built around roles published on [Ansible Galaxy][Galaxy] by the
community. This is also were we published the [Open Notificaties Collection][collection],
which provides Open Notificaties-specific roles.

## Requirements

* A server with a supported Linux distribution (see the Ansible Collection docs for
  supported distros).
* Root access to the server
* SSH access (with the root user)
* A python virtualenv with the [requirements](../requirements.txt) installed

## Deployment

Follow the guide in the [official documentation][docs] - the steps still apply.


[docs]: https://open-notificaties.readthedocs.io/en/stable/installation/deployment/single_server.html
[Ansible]: https://www.ansible.com/
[Galaxy]: https://galaxy.ansible.com/
[collection]: https://github.com/open-zaak/ansible-collection
