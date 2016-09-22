magic-glass-secrets
=====================

An example set of secrets for [Magic Glass](https://github.com/getglass/magic-glass). You should use this to create your "secrets" repository.

Be careful submitting pull requests for magic-glass-secrets; by design this can contain passwords,
certificates and other sensitive data!

Getting Started
===============

Usage
-----
* Run the following command in order to create keys. You should be standing in your Projects folder (within which magic-glass and magic-glass-secrets exist), not inside the MG folders.

` ssh-keygen -f ./magic-glass-secrets/ssh/id_rsa`

* Run the following command to set up links

` ln -s ../magic-glass-secrets/ ./magic-glass/secrets`

Note, if you are using different repository names you will need slightly modified commands. Example:

` ssh-keygen -f ./av-deploy-secrets/ssh/id_rsa`

` ln -s ../av-deploy-secrets/ ./av-deploy/secrets`
