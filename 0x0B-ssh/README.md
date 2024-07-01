# 0x0B. SSH

This project covers SSH (Secure Shell) concepts and usage in DevOps and system administration.

## Files

### 0-use_a_private_key

Bash script that uses ssh to connect to a server using the private key `~/.ssh/school` with the user ubuntu.

### 1-create_ssh_key_pair

Bash script that creates an RSA key pair.

### 2-ssh_config

SSH client configuration file set up to use the private key `~/.ssh/school` and refuse password authentication.

### 100-puppet_ssh_config.pp

Puppet manifest to make changes to the SSH client configuration file.

## Learning Objectives

By the end of this project, you should be able to explain:

- What is a server
- Where servers usually live
- What is SSH
- How to create an SSH RSA key pair
- How to connect to a remote host using an SSH RSA key pair
- The advantage of using `#!/usr/bin/env bash` instead of `/bin/bash`

## Requirements

- All files interpreted on Ubuntu 20.04 LTS
- All files should end with a new line
- All Bash script files must be executable
- The first line of all Bash scripts should be `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what the script does

## Author

- Dagmawi Y.
