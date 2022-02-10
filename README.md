<img src="https://www.funkysheep.net/img/Logo-Head-Mini.png" alt="drawing" width="200"/>

# Infra
Devops infrastructure managment for FunkySheep Studio company

Based on Github action, allow to build the company infrastructure from scratch on a fresh Ubuntu Installation via SSH.

- Prerequisites:
    -   Your devops user must be able to connect to SSH to the remote host.

    -   The following secrets entries must bu configured for the ssh connection to be established:
        -   HOST
        -   USER
        -   PASSWORD

    -   Add a sudo configuration file to "/etc/sudoers.d/" for your devops user with the following no password settings:

        youruser ALL=(ALL) NOPASSWD:ALL

        It will enable to run "sudo" command without password prompt.
