# 0x13. Firewall

## Description
This project involves configuring a firewall using `ufw` to manage and secure network traffic. It includes setting rules to allow specific ports and port forwarding.

## Files
- **0-block_all_incoming_traffic_but**: Bash script with `ufw` commands to block all incoming traffic except on TCP ports 22 (SSH), 80 (HTTP), and 443 (HTTPS).
- **100-port_forwarding**: Configuration file for `ufw` to forward traffic from port 8080/TCP to port 80/TCP.

## Requirements
- Tasks should be applied to the server `web-01`.
- Ensure `ufw` is installed and active on the server.
- All configurations should be verified for correct functionality.

## Author
- Dagmawi Y.
