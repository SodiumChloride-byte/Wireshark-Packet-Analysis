# Packet Capture Report

## Protocols Identified

1. **HTTPS**

Port: TCP/443

Role: Secure version of HTTP, encrypted with TLS.

In Capture: TLS handshake observed, with possible OCSP certificate checks.

2. **DNS**
   
Typical Ports:

UDP/53 (most common)

TCP/53 (for larger queries/responses)

Role: Translates domain names (like google.com) into IP addresses.

In Capture:

DNS Query: A tryhackme.com

DNS Response: 104.26.10.229

3. **TCP**

Typical Ports:

Ephemeral source port (random high number, e.g., 49152+)

Destination port depends on application:

Port 80 (HTTP)

Port 443 (HTTPS/TLS)

Role: Provides reliable, connection-oriented communication. Ensures packet delivery with acknowledgments.

In Capture:

3-Way Handshake observed:

SYN → SYN-ACK → ACK

Data packets exchanged after handshake.

## Summary
The capture contained multiple protocols. HTTP traffic showed web requests, DNS was used to resolve hostnames, and TCP provided reliable data transfer. Together, they represent typical web browsing activity.
