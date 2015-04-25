# guardsshd
Guard against malicious SSH connection attempts

`guardsshd` monitors and blocks against ssh connections that are considered suspicious or malicious.

# Blocked IPs

SSH attempts with the following behaviors are considered malicious:
- Connection attempts on multiple ports
- Consistent connection interval patterns
- TOR network addresses
- Unexpected IP address geolocation
- IP addresses or subnets outside of whitelist
