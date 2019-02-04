ansible-playbook-init-unseal-vault
=========

Initialize and unseal a vault cluster using multiple key shards.

Requirements
------------

An uninitialized and sealed vault cluster.

Playbook Variables
--------------

    display_init_response: false
    tls_skip_verify: true
    vault_secret_shares: 3
    vault_secret_threshold: 2
    vault_tls_disable: true
