# Ansible Collection - nightly_brew.ansible_containers_host

This collection takes care of setting up a linux machine to run OCI containers.

There are two roles available under this collection:
- podman_host
- docker_host (TBA)

They both setup the targeted host with the chosen container engine.
For the podman_host role, docker-compose is downloaded as well from the github repository to provide the best compatibility with `docker compose`.
