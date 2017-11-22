# HarmonicIOSetup
Ansible playbooks for installing and starting Harmonic IO on a virtual environment.

# Installation and setup

The setup requires an working ansible environment with VMs available to deploy HIO workers 

Run the install_ansible script to install ansible then edit the Hosts file with the IPs to your workers and add more workers if necessary.

Ports for the master and workers can be edited inside the deployHIO.yml script
