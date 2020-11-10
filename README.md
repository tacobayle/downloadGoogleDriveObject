# downloadGoogleDriveObject

## Goals
Download an object/file from Google drive 
 
## Prerequisites:
- Make sure the following variables are defined: googleDriveId and outputFile
- Make sure Ansible is installed in the orchestrator VM with Internet connection

## Environment:

### Ansible

```
ansible 2.9.12
  config file = None
  configured module search path = ['/home/nic/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /home/nic/.local/lib/python3.8/site-packages/ansible
  executable location = /home/nic/.local/bin/ansible
  python version = 3.8.2 (default, Jul 16 2020, 14:00:26) [GCC 9.3.0]
```

## Run the playbook:
```
ansible-playbook local.yml
```
