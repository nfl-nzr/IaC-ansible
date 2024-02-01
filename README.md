# Kubernetes HA cluster
An automated kubernetes HA cluster using k3s and ansible.
This will install k3s on the specified master and slave nodes along with the dependencies and convert slaves to agents.
Create .vault_pass file for passwords
export env var ANSIBLE_VAULT_PASSWORD_FILE=./.vault_pass

# TODO
[ ] Organize better !!!!
[ ] Pin versions!!!