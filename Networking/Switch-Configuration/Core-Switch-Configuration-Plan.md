# Retail Enterprise - Core Switch Configuration Plan

## Purpose

This document defines the planned configuration for the Core Switch in the Retail Enterprise network.

---

## Switch Name

Core-SW1

---

## VLAN Configuration

| VLAN ID | VLAN Name |
|----------|-----------|
| 10 | Management |
| 20 | Web |
| 30 | Application |
| 40 | Database |
| 50 | Future |

---

## Access Ports

| Port | Connected Device | VLAN |
|------|-------------------|------|
| Gi0/1 | Web Server | 20 |
| Gi0/2 | Application Server | 30 |
| Gi0/3 | Database Server | 40 |

---

## Trunk Port

| Port | Connected Device | Allowed VLANs |
|------|-------------------|---------------|
| Gi0/24 | Access Switch | 10,20,30,40,50 |

---

## Notes

- Access ports carry traffic for one VLAN.
- Trunk ports carry traffic for multiple VLANs.
- VLAN 50 is reserved for future expansion.
- This document will be used during switch configuration.