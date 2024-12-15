# Ansible readme

I want to make some notes about these yaml files and what they do with Ansible.

I guess the first thing is understanding Ansible inventories. An inventory is just a list of hosts or nodes. It doesnt have to be network switches or something. I *think* the tasks listed for the install, set_fleet, and post_install files are using a node inventory where the nodes are docker (or podman) containers.

the inventory is combined with some tasks, but I don't understand that part yet...
