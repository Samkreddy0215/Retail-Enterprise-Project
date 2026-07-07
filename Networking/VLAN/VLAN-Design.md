# Retail Enterprise - VLAN Design

## Purpose

This document defines the VLANs used in the Retail Enterprise network.

---

## VLAN 10 - Management

Purpose:
Used by IT administrators to manage network devices and servers.

Devices:
- Administrator PC
- Network Switches
- Firewall Management Interface

---

## VLAN 20 - Web Servers

Purpose:
Hosts the web servers that receive customer requests.

Devices:
- Web Server

---

## VLAN 30 - Application Servers

Purpose:
Runs the business logic of the Retail Enterprise application.

Devices:
- Application Server

---

## VLAN 40 - Database Servers

Purpose:
Stores customer, product, and order information.

Devices:
- Database Server

---

## VLAN 50 - Future Expansion

Purpose:
Reserved for future servers and services.

| VLAN ID | VLAN Name   | Devices            |
| ------- | ----------- | ------------------ |
| 10      | Management  | Admin PC, Switches |
| 20      | Web         | Web Server         |
| 30      | Application | Application Server |
| 40      | Database    | Database Server    |
| 50      | Reserved    | Future Use         |
