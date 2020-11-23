# how to use

* learn ansible
* modify hosts_example
* ansible-playbook ./kafka.yml -i ./hosts_example/ --user=root -b --become-user=work --tags start # ssh as root,  run as work, cfg = change config, deploy = scp, untar, cfg, start
