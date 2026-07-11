# Firewall
# Global IP Blocklist for qBittorrent (P2B Format)

A comprehensive, regularly updated `.p2b` blocklist designed to protect your privacy and security while using qBittorrent. This list aggressively blocks:

- 🚫 **All known IP ranges originating from Israel** (including military, government, and commercial ASNs)
- 🚫 **Over 205,000+ malicious IPs** worldwide, including:
  - Known surveillance & data-mining networks
  - Botnet C2 servers
  - Honeypot and logging peers
  - Spam & DDoS sources
  - Government-backed threat actors

**File Format:** `.p2b` (PeerBlock binary format) — optimized for qBittorrent's IP filter engine.  
**Total entries:** Compressed binary representation of **tens of thousands of IP ranges** (equivalent to 200,000+ individual addresses).  
**Recommended use:** Load this file in qBittorrent's **qbittorrent → Prefernces → Connection → IP Filtering → browse & select GreatFirewallOfChina.p2p → tick the filter path** for automatic, real-time blocking.

