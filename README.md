# RAW Ansible

This repository contains a playbook which will configure servers.
This also contains individual roles used for setting up servers (e.g. autologon, onair) as well as common tasks.

## Running

When on the control server you can run `ansible-playbook playbook.yml` to run the entire playbook. *Warning* this will take a long time!

If you wish to run this on a subset of servers you can use the `-l` tag. e.g. `ansible-playbook playbook.yml -l onair` will just run the playbook on the onair hosts.

## Vault

Some variables are stored in the vault. These will automatically be decrypted when run (note: vault files are not commited to git) `ansible.cfg` specifies the vault password location.