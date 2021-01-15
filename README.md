# ansible_storagegrid

Sample Ansible playbook and vars for StorageGRID.

Step 1: Edit sg_vars.yaml and update the StorageGRID hostname to point to your instance (without a trailing slash).
Step 2: Run the playbook:

```
$ ansible-playbook sg_demo.yaml
```

Original source: https://netapp.io/2020/06/26/Automating-StorageGRID-Operations-with-Ansible/
