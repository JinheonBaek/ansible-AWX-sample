# Ansible-Playbook Sample for Installing Intellij, Eclipse
This is a sample code (like toy) for installing intellij, eclipse on cloud infra. <br>

### There are two softwares that can be installed or uninstalled.
1. Intellij
2. Eclipse

### Also we provide two options for installing software
1. Install software manually.
2. Install software using ansible-galaxy.

#### Note
If you want to install software via ansible-galaxy, your workspace shold be setup properly. <br>
For the detail, follow ansible (AWX) docs. <br>
Uninstall software will not be worked properly, it is forced delete and some environment setting may be remaining. <br>
Recommend way of installing and uninstalling software is installing manually (not ansible-galaxy, ansible-galaxy will make issue when uninstalling software).