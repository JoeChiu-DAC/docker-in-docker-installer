# Ansiable Playbook Docker in Dokcer Automation Installer

## Synopsis
This ansible playbook will install a jenkins system either by docker in docker on a Ubuntu box or docker client in docker on a CentOS based on the inventory distribution global variable. 

## Linux RHEL 7.5
* Ansible: 2.7.5
* Docker: 1.13.1
* Jenkins container: 2.121.1 (openshift/jenkins-2-centos7)
* Python: 2.7.5
* Platform: Google Cloud Platform

## Linux Ubuntu 16.04
* Ansible: 2.5.2
* Docker: 18.05.0-ce
* Jenkins container: 2.60.3 (jenkins:latest)
* Python: 2.7.12
* Platform: VirtualBox

## Command
time sudo ansible-playbook -vvv jenkins-in-docker.yml

## License
A short snippet describing the license (MIT, Apache, etc.)

