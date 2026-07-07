# Retail Enterprise - Network Zones

## Purpose

The Retail Enterprise network is divided into different zones to improve security and simplify network management.

## Zone 1 - Public Zone

Purpose:
Receives traffic from customers on the Internet.

Contains:
- Firewall
- Load Balancer

## Zone 2 - Application Zone

Purpose:
Hosts the application servers that process customer requests.

Contains:
- Web Server
- Application Server

## Zone 3 - Database Zone

Purpose:
Stores business data securely.

Contains:
- Database Server

Only the Application Server is allowed to communicate with the Database Server.

Direct access from the Internet is not allowed.