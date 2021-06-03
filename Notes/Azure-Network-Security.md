# Azure Network Security

## Network Security Groups

NSG is a static set of rules which protects the network, also known as Access Control List.
Certain IPs will have access to certain ports only, It is deny by default.
A virtual network can be divided into subnets, we can have public facing services on a separate subnet and the critical back end services on a more protected subnet.

## Azure Firewall

An intelligent traffic analysis tool that matches incoming traffic to see if it matches certain bad patterns like SQL injection, CORS etc.

## Azure DDoS Protection

- Basic

  - Provides always on monitoring
  - Automatic mitigation for L3/L4 attacks (Network layer, TCP attacks)
  - L7 Protection with Application gateway web application firewall
  - Globally Deployed

- Standard

  - Is designed specifically for your VNet.
  - Has logging, alerting and telemetry
  - Resource cost scale protection
  - Plus all basic features
