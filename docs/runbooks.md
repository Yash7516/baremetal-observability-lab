# Runbooks

## Service down
- check status: systemctl status <service>
- check logs: journalctl -u <service> -n 200 --no-pager
- restart: sudo systemctl restart <service>

## High CPU
- top / htop
- check alerts + dashboard
- identify process + mitigate
