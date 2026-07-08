# Retail Enterprise - Switch Port Assignment

## Purpose

This document defines how the switch ports are assigned to servers and network devices.

---

## Switch Information

Switch Name: Access-SW1

---

## Port Assignment Table

| Port | Connected Device | VLAN | Port Type |
|------|-------------------|------|-----------|
| Gi0/1 | Web Server | VLAN 20 | Access |
| Gi0/2 | Application Server | VLAN 30 | Access |
| Gi0/3 | Database Server | VLAN 40 | Access |
| Gi0/4 | Load Balancer | VLAN 20 | Access |
| Gi0/24 | Core Switch | VLAN 10,20,30,40 | Trunk |

---

## Notes

- Web Server is connected to VLAN 20.
- Application Server is connected to VLAN 30.
- Database Server is connected to VLAN 40.
- The trunk port carries traffic for multiple VLANs.
- This document will be used during switch configuration.