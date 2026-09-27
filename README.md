# Wireshark Network Traffic Analysis Lab

## Objective
Analyze common network protocols using Wireshark and develop
hands-on packet analysis skills.

## Environment
- Windows
- Wireshark
- Command Prompt
- Home lab network

## DNS Analysis

I generated DNS traffic using:

nslookup example.com

I observed a DNS response with:
- Source: DNS server
- Destination: Local workstation
- Source Port: 53
- Destination Port: Ephemeral client port

This demonstrated how a client sends a DNS query to port 53
and receives the response on the temporary port created for
the transaction.

## ARP Analysis
...

## ICMP Analysis
...

## TCP Analysis
...

## TLS Analysis
...

## Key Takeaways
...
