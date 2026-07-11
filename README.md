# Global IP blocklist for qBittorrent

A curated `.p2p` blocklist that prevents unwanted peers from connecting to your torrents.

## What it blocks

- All IP ranges allocated to Israel (ISP and residential — no cloud/CDN noise)
- Datacenter and hosting ranges used by scanners and scrapers
- Anti-P2P monitoring organizations (MediaSentry, BayTSP, etc.)
- Known botnet infrastructure and malicious actor ranges

## File details

| Property | Value |
|---|---|
| Format | `.p2p` — plain text, eMule/qBittorrent compatible |
| Total ranges | ~202,000+ |
| Israel ranges | 1,599 (ISP and residential only) |
| IP source | db-ip.com country lite + curated threat lists |

## How to load in qBittorrent

1. Open qBittorrent → **Preferences → Connection**
2. Under *IP Filtering*, tick **Filter path**
3. Browse and select `cleaned.p2p`
4. Click **OK** — takes effect immediately
