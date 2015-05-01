looking-glass-secrets
=====================

An example set of secrets for Magic Glass. You should use this to create your "secrets" repository.

Be careful submitting pull requests for magic-glass-secrets; by design this can contain passwords,
certificates and other sensitive data!

Getting Started
===============

Usage
-----
* Run the following commands in order to create keys and link necessary variables.

` ssh-keygen -f ./magic-glass-secrets/ssh/id_rsa`

`ln -s ../magic-glass-secrets/group_vars ./magic-glass/group_vars`

`ln -s ../magic-glass-secrets/vars ./magic-glass/vars`
