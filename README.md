# Ansibledocs
# Ansible Nginx Deployment

This playbook installs and starts Nginx on web servers.

## Run

Test connectivity:

```bash
ansible webservers -m ping
```

Run the playbook:

```bash
ansible-playbook deploy.yml
```

The playbook will:

* Install Nginx
* Start Nginx
* Enable Nginx at boot
