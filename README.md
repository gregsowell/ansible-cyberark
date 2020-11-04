# ansible-cyberark
Ansible automation with Cyberark products

# Playbooks
conjur-install-config.yml - this takes a clean server, then builds the full conjur environment and populates a couple of secrets.  I designed and tested this on a centos8 box.  Blog post on it here: http://gregsowell.com/?p=6585
network.yml.j2 - this is the policy file used to build the conjur infrastructure.
