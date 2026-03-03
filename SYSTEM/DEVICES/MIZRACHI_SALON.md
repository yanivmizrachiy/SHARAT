# DEVICE — SALON PC (CENTRAL NODE)
Last Update: 2026-03-03 12:52

Hostname: MIZRACHI
Tailscale IPv4: 100.99.185.100
Role: CENTRAL ALWAYS-ON NODE (salon)

SSH:
- Service: sshd (Automatic)
- Port: 22
- Firewall: allow ONLY via InterfaceAlias 'Tailscale'

Notes:
- Password auth currently ON (temporary). After Termux key is installed, switch to key-only.
