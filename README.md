# Ansiable Playbook Docker in Dokcer Automation Installer

## Synopsis
This ansible playbook will install a jenkins system either by docker in docker on a Ubuntu box or docker client in docker on a CentOS box based on the inventory distribution global variable. 

## Linux RHEL 7.5
* Ansible: 2.7.5
* Docker: 1.13.1
* Jenkins container: 2.121.1 (openshift/jenkins-2-centos7)
* Python: 2.7.5
* Platform: Google Cloud Platform
* https://github.com/joehmchiu/docker-client-in-docker

## Linux Ubuntu 16.04
* Ansible: 2.5.2
* Docker: 18.05.0-ce
* Jenkins container: 2.60.3 (jenkins:latest)
* Python: 2.7.12
* Platform: VirtualBox
* https://github.com/joehmchiu/docker-in-docker-ubuntu

## INSTALL
cd /tmp && curl -O https://raw.githubusercontent.com/joechiu/docker-in-docker-installer/master/jenkins-in-docker.yml && time ansible-playbook -v jenkins-in-docker.yml

## Command
time sudo ansible-playbook -vvv jenkins-in-docker.yml

## REFERENCES
* https://stackoverflow.com/questions/28089344/docker-what-is-it-and-what-is-the-purpose

## License
A short snippet describing the license (MIT, Apache, etc.)

