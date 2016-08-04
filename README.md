OpenVPN Installation and Configuration

This script allows you to install and configure OpenVPN on Centos 7. This script sets up openvpn configurations, unbound recursive dns setup, blocks advertisements/malware/tracking domains by DNS, and employs extremely hardened settings.

Make sure you run all the scripts!

Security:
- Minimum TLS Version 1.2
- SHA512 HMAC Authentication
- TLS Authentication Secret
- Checks Extended Key Usage
- Verifies X.509 Subject Names
- 4096-bit RSA
- TLS ciphers TLS-ECDHE-RSA-WITH-AES-128-GCM-SHA256:TLS-ECDHE-ECDSA-WITH-AES-128-GCM-SHA256:TLS-ECDHE-RSA-WITH-AES-256-GCM-SHA384:TLS-DHE-RSA-WITH-AES-256-CBC-SHA256

How to Install:
- Run openvpn.sh
- Run adblock.sh
- Run client.sh
- Transfer the configuration files to your host

Old Files:
https://github.com/jonathanwalker/openvpn
