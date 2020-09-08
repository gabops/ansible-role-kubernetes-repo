gabops.kubernetes_repo
=========
![Build Status](https://github.com/gabops/ansible-role-kubernetes-repo/workflows/Molecule%20CI/badge.svg?branch=master)

Installs and configures the official Kubernetes repository.


Requirements
------------

None.


Role Variables
--------------

| Variable | Default value | Description |
| :--- | :--- | :--- |
| kubernetes_repo_state | present | Controls if the repository is installed (present) or uninstalled (absent). |
| kubernetes_repo_enabled | true | Controls if the repository is enabled (true) or disabled (false). |


Dependencies
------------

None.


Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: gabops.kubernetes_repo
```


License
-------

[MIT]((./LICENSE))


Author Information
------------------

Gabriel Suarez ([Gabops](https://github.com/gabops))
