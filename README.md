# Kubernetes-Install-Fedora

### Description

Ansible script that installs a Kubernetes cluster on fedora machines. Hopefully it would work on any RHEL based distro.

See: [https://www.relay70.com/2024/10/03/kubernetes-fedora-39/](https://www.relay70.com/2024/10/03/kubernetes-fedora-39)

for the manual steps.

### Usage

* Edit your inventory file and enter your Kubernetes master and  node machines under the appropriate sections.
* Execute: ansible-playbook main.yml -i inventory -u <user> --ask-pass
