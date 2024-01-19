# prov__steam
ansible role for steam provisioning

# requirements
# variables
# dependencies
# examples
```
---

- name: usage example
  hosts: target_hosts

  tasks:

    - name: deploy steam
      ansible.builtin.include_role:
        name: prov__steam
        tasks_from: steam.yml

    - name: steam via sudo
      ansible.builtin.include_role:
        name: prov__steam
        tasks_from: sudo.yml

...
```
