# IP Blocklists for qBittorrent

A collection of curated `.p2p` blocklists that prevent unwanted peers from connecting to your torrents.

## Available blocklists

### `block_only_il.p2p` — Israel IP ranges only
A compact blocklist targeting Israel-allocated IP ranges (ISP and residential — no cloud/CDN noise).

### `GreatFirewallOfChina.p2p` — Comprehensive global blocklist
Blocks multiple threat categories:
- All IP ranges allocated to Israel (ISP and residential)
- Datacenter and hosting ranges used by scanners and scrapers
- Anti-P2P monitoring organizations (MediaSentry, BayTSP, etc.)
- Known botnet infrastructure and malicious actor ranges

## File details

| Property | Value |
|---|---|
| Format | `.p2p` — plain text, eMule/qBittorrent compatible |
| **block_only_il.p2p** | Israel ranges only (~1,599 ranges) |
| **GreatFirewallOfChina.p2p** | ~202,000+ ranges (comprehensive) |
| IP source | maxmind.com's GeoLite Country + curated threat lists |

## How to load in qBittorrent

1. Open qBittorrent → **Preferences → Connection**
2. Under *IP Filtering*, tick **Filter path**
3. Browse and select the blocklist file you want to use (`block_only_il.p2p` or `GreatFirewallOfChina.p2p`)
4. Click **OK** — takes effect immediately
