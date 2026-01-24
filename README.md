# WireGuard VPN Gateway

A secure VPN gateway built using WireGuard that routes client traffic through a host machine with NAT, firewall rules, and DNS forwarding.

## Features
- WireGuard VPN server configuration
- Secure routing and NAT rules
- DNS forwarding and traffic isolation
- Supports mobile and desktop clients

## Tech Stack
- WireGuard
- Linux / Windows
- iptables / routing rules
- Bash / PowerShell

## Architecture
Client → WireGuard Tunnel → Gateway Host → Internet

## How to Run
1. Install WireGuard
2. Configure wg0.conf
3. Enable IP forwarding
4. Apply routing and NAT rules
5. Start the WireGuard interface

## Screenshots
Add screenshots here

## Security Notes
- Keys are generated locally and never committed
- Firewall rules restrict unwanted access

## Future Improvements
- GUI dashboard
- Logging and monitoring
