# Networking

A collection of hands-on technical labs documenting low-level packet mechanics, network reconnaissance, host-based firewall policies, cryptographic session security, and network attack analysis using Wireshark, Nmap, Netfilter (`iptables`), and Linux network security tools.

---

## Portfolio Lab Index

* **[01. Core Protocol Analysis (ARP, ICMP, DNS, TCP)](./01-core-protocol-analysis)** — Wireshark packet capture and protocol breakdown covering baseline ARP resolutions, ICMP echo flows, DNS queries, and TCP 3-way handshakes.
* **[02. Nmap Reconnaissance Mechanics & Low-Level Packet Analysis](./02-nmap-recon-analysis)** — Packet-level analysis of Nmap scan mechanics across TCP SYN (`-sS`), Connect (`-sT`), Xmas (`-sX`), Null (`-sN`), and ACK (`-sA`) techniques.
* **[03. Host-Based Firewall Filtering Analysis (`iptables`)](./03-firewall-filtering-analysis)** — Kernel packet filtering evaluation comparing silent `DROP` vs. active `REJECT` policies, ICMP ping suppression, and targeted source IP Access Control Lists (ACLs).
* **[04. Encrypted Session & TLS Protocol Mechanics (HTTP vs. HTTPS)](./04-tls-session-analysis)** — Deep packet inspection evaluating plain-text HTTP payload vulnerabilities vs. TLS 1.2 encrypted sessions, cryptographic handshakes, and public key certificate exchanges.
* **[05. Network Attack Analysis & Incident Response (ARP Poisoning & TCP SYN Flood)](./05-network-attack-analysis)** — Deep packet inspection and incident response analysis covering Layer 2 ARP Cache Poisoning (Man-in-the-Middle) and Layer 4 TCP SYN Flood (Denial of Service) attack vectors.
