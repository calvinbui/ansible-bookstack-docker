# Ansible BookStack

BookStack in Docker

##  Requirements

N/A

## Role Variables

`bookstack_name`: Name of container

`bookstack_image`: Docker image to  use

`bookstack_volumes`: Directory to store configuration files

`bookstack_ports`: List of ports to expose

`bookstack_docker_additional_options`: [Additional parameters](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) to add to docker container

`bookstack_environment_variables`: Docker environmental variables

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
   - role: calvinbui.ansible_bookstack_docker
```

## License

GPLv3

## Author Information

http://calvin.me
