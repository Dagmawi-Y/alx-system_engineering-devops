# 0x0F. Load Balancer

## Overview
This project involves configuring a load balancer and multiple web servers to improve traffic handling and redundancy. The setup includes adding custom headers in Nginx, setting up HAProxy, and automating these processes with scripts.

## Tasks

### Task 0: Double the number of web servers
- **Objective**: Configure `web-02` to be identical to `web-01` and add a custom HTTP response header.
- **Script**: `0-custom_http_response_header`
- **Requirements**:
  - Nginx HTTP response must contain a custom header `X-Served-By` with the hostname of the server.

### Task 1: Install your load balancer
- **Objective**: Install and configure HAProxy on `lb-01` to distribute traffic between `web-01` and `web-02`.
- **Script**: `1-install_load_balancer`
- **Requirements**:
  - Configure HAProxy to use the round-robin algorithm.

### Task 2: Add a custom HTTP header with Puppet
- **Objective**: Automate the creation of a custom HTTP response header using Puppet.
- **Script**: `2-puppet_custom_http_response_header.pp`
- **Requirements**:
  - The header name should be `X-Served-By` with the value set to the server's hostname.

## Repository Structure
- `0-custom_http_response_header`: Bash script for configuring Nginx on a new server.
- `1-install_load_balancer`: Bash script for installing and configuring HAProxy.
- `2-puppet_custom_http_response_header.pp`: Puppet manifest for setting up the custom HTTP header.
- `README.md`: Project documentation.
