ansible-role-vault
=========

Install Hashicorp Vault, production mode on multiple hosts (HA)

Role Variables
--------------

```yaml
vault_version: "1.3.2"
vault_sha256: "6e72132de0421b74d909f50be1823fe57182694c4268ba9a38c31213d9497ec9"
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vault-ha }

License
-------

GPL-v3

