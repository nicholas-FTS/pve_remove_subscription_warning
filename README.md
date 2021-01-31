Proxmox Remove Subscription Warning
=========

Remove the subscription warning in the Proxmox GUI.

Current version: `v0.1.0`

Requirements
------------

A node with Proxmox installed.

Role Variables
--------------

### `defaults/main.yml`:
None.

### `vars/main.yml`:

```
pve_proxmoxlib_js_file: /usr/share/javascript/proxmox-widget-toolkit/proxmoxlib.js
```
The path of the file that contains the subscription warning source code on the proxmox node.

Dependencies
------------

None.

Example Playbook
----------------

```YAML
- hosts: servers
  roles:
    - pve_remove_subscription_warning
```

License
-------

GPLv3

Author Information
------------------

Nicholas Morey / nicholas@frontenac.tech
