looking-glass-secrets
=====================

An example set of secrets for Looking Glass. You should use this to create your "secrets" repository.

Be careful submitting pull requests for looking-glass-secrets; by design this can contain passwords,
certificates and other sensitive data!

Getting Started
===============

Usage
-----
* Use Git to clone looking-glass-secrets into the same folder you have looking-glass in.
* Change into the looking-glass-secrets directory.
* Run 'ssh-keygen -f ./ssh/id_rsa'
* [DOESN'T CURRENTLY APPLY] Set a suitably strong passphrase
* Run 'cd ../looking-glass'
* Run 'ln -s ../looking-glass-secrets/group_vars group_vars' to set up your group variables folder.
* Run 'ln -s ../looking-glass-secrets/vars vars' to set up your main variables folder.
