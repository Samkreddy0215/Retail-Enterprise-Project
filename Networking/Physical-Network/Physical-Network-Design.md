# Retail Enterprise - Physical Network Design

## Purpose

This document describes the physical devices required for the Retail Enterprise infrastructure.

---

## Network Devices

### Internet Connection

Provides connectivity between customers and the Retail Enterprise application.

---

### Edge Router

Connects the organization to the Internet Service Provider (ISP).

---

### Next Generation Firewall

Protects the internal network from unauthorized access.

Performs:

- Packet Filtering
- NAT
- VPN
- Intrusion Prevention

---

### Core Switch

Acts as the backbone of the internal network.

Connects:

- Firewall
- Access Switch
- Servers

---

### Access Switch

Provides network connectivity for servers.

---

### Load Balancer

Distributes incoming traffic to web servers.

---

### Web Server

Hosts the Retail Enterprise website.

---

### Application Server

Runs business logic.

---

### Database Server

Stores customer, inventory, and order data.