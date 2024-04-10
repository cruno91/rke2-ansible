# Ansible playbook for RKE2 cluster

This playbook will install RKE2 on a set of 3 server nodes, 3 agent nodes, and
a load balancer for the 3 servers.

1. `ansible-playbook -i inventory.ini rke2.yml --check`
2. `ansible-playbook -i inventory.ini rke2.yml`