# openshift-prepare
Ansible role and playbooks to prepare a new OpenShift version 3 installation

You can only sue main.yml 

Main will include:
- include_tasks: disks.yml
- include_tasks: packages.yml
- include_tasks: dnscheck.yml
