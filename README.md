# Networking

A collection of hands-on technical labs documenting low-level packet mechanics, network reconnaissance, host-based firewall policies, and cryptographic session security analyzed using Wireshark, Nmap, and Linux network administration tools.

---

## Portfolio Lab Index

* **[01. Core Protocol Analysis (ARP, ICMP, DNS, TCP)](./01-core-protocol-analysis)** — Wireshark packet capture and protocol breakdown covering baseline ARP resolutions, ICMP echo flows, DNS queries, and TCP 3-way handshakes.
* **[02. Nmap Reconnaissance Mechanics & Low-Level Packet Analysis](./02-nmap-recon-analysis)** — Packet-level analysis of Nmap scan mechanics across TCP SYN (`-sS`), Connect (`-sT`), Xmas (`-sX`), Null (`-sN`), and ACK (`-sA`) techniques.
* **[03. Host-Based Firewall Filtering Analysis (`iptables`)](./03-firewall-filtering-analysis)** — Kernel packet filtering evaluation evaluating silent `DROP` vs. active `REJECT` policies, ICMP ping suppression, and targeted source IP Access Control Lists (ACLs).
* **[04. Encrypted Session & TLS Protocol Mechanics (HTTP vs. HTTPS)](./04-tls-session-analysis)** — Deep packet inspection evaluating plain-text HTTP payload vulnerabilities vs. TLS 1.2 encrypted sessions, cryptographic handshakes, and public key certificate exchanges.
