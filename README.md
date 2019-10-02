# Ansible Container Image#

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/geoffh1977/ansible.svg?style=plastic)
![GitHub](https://img.shields.io/github/license/geoffh1977/docker-ansible.svg?style=plastic)

## Description ##
An Alpine based ansible container. Ansible is used for configuration as code management of systems.

## Starting The Container ##
To run the container in interactive mode:

```
docker run -it --rm -v $(pwd):/project geoffh1977/ansible
```

The container can also be run in a non-interactive mode by specifying the full ansible command after the docker command.

## Building The Ansible Container ##
After cloning the repository, simply execute a regular docker build command to build the container from scratch.

### Getting In Contact ###
If you find any issues with this container or want to recommend some improvements, fell free to get in contact with me or submit pull requests on github.
