# 0x0C. Web Server

This directory contains scripts to configure and manage a web server on an Ubuntu 16.04 system.

## Files

- **0-transfer_file**: Bash script to transfer a file from a local machine to a remote server using `scp`.

- **1-install_nginx_web_server**: Bash script to install and configure Nginx on a server to respond with "Hello World!" on the root path.

- **2-setup_a_domain_name**: Contains the domain name configured to point to the web server's IP address.

- **3-redirection**: Bash script to configure a 301 redirection on the Nginx server.

- **4-not_found_page_404**: Bash script to set up a custom 404 error page on the Nginx server displaying "Ceci n'est pas une page".

- **7-puppet_install_nginx_web_server.pp**: Puppet manifest to automate the installation and configuration of Nginx, including setting up a 301 redirect.
