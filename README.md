# Ansible-NTP-server-and-client-install-config
This was created as an excercise for school.

This playbook is to be used for setting up an Ansible controller as NTP server and installing ntp on ubuntu client and configuring it.
Aswell as installing chrony for fedora ntp clients.
In case u want to only use it for fedora it has been split up into different roles where u can find the play u might need in the corresponding role's tasks folder with the name main.yaml.

If u wish to use this please also look at the inventory file and change it as needed for your own network/devices.

If u wish to just run the full playbook this can be found in the NTP server&client playbook folder.

For the ubuntu client i used ntpd and for the Fedora client chrony.

