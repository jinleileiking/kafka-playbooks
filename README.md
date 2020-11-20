# how to use

* learn ansible
* modify hosts
* ansible-playbook ./kafka.yml -i ./hosts/ --user=root -b --become-user=work --tags start # ssh as root,  run as work, cfg = change config, deploy = scp, untar, cfg, start
