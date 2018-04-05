# launch the playbook

```bash
 sudo echo "localhost ansible_connection=local" >>/etc/ansible/hosts
 ansible-playbook set-me-up.yml  --ask-become-pass
```