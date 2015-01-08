looking-glass-secrets
=====================

An example set of secrets for Looking Glass. You should use this to create your "secrets" repository.

Be careful submitting pull requests for looking-glass-secrets; by design this can contain passwords,
certificates and other sensitive data!

Getting Started
===============

Usage
-----
* Run the following commands in order to create keys and link necessary variables.

` ssh-keygen -f ./looking-glass-secrets/ssh/id_rsa`

`ln -s ../looking-glass-secrets/group_vars ./looking-glass/group_vars`

`ln -s ../looking-glass-secrets/vars ./looking-glass/vars`
