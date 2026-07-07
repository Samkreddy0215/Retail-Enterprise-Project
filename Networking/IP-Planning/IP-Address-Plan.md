# Retail Enterprise - IP Address Plan

## Network

Network Address: 10.0.0.0/24

## Devices

| Device | Purpose | IP Address |
|---------|---------|------------|
| Firewall | Default Gateway | 10.0.0.1 |
| Load Balancer | Distributes traffic | 10.0.0.10 |
| Web Server | Hosts the website | 10.0.0.20 |
| Application Server | Runs business logic | 10.0.0.30 |
| Database Server | Stores application data | 10.0.0.40 |

## Notes

- All servers use static IP addresses.
- The Firewall acts as the gateway.
- Each server has a unique IP address.