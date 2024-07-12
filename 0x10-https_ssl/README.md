# 0x10. HTTPS SSL

## Files

- `0-world_wide_web`: Script to configure and display DNS subdomains.
- `1-haproxy_ssl_termination`: HAProxy config for SSL termination.
- `100-redirect_http_to_https`: HAProxy config to redirect HTTP to HTTPS.

## Usage

### 0-world_wide_web
```bash
./0-world_wide_web <domain> [subdomain]
```

### HAProxy Configuration
- Place 1-haproxy_ssl_termination in /etc/haproxy/haproxy.cfg for SSL termination.
- Place 100-redirect_http_to_https in /etc/haproxy/haproxy.cfg to redirect HTTP to HTTPS.