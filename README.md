# Add PHP Extension

A simple ansible script to add PHP extensions.

1. Create a variable file based on `oauth.yml`.
2. Replace the `oauth.yml` entry from `var_files` in `playbook.yml` with the file you just made.
3. Add a `vault.yml` with the `vault_ansible_become_pass` variable.
