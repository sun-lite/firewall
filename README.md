# IP Blocklists for qBittorrent

A collection of curated `.p2p` blocklists that prevent unwanted peers from connecting to your torrents.

> **Discontinued: `GreatFirewallOfChina.p2p`** — This comprehensive blocklist is discontinued due to the huge work required to maintain the threat list (datacenter, anti-P2P, botnet, etc.). From now on this repo will publish only `block_only_il.p2p`, which contains the list of all Israeli IP ranges and is updated monthly.

## Available blocklists

### `block_only_il.p2p` — Israel IP ranges only (actively maintained)
A compact blocklist targeting all Israel-allocated IP ranges (ISP and residential — no cloud/CDN noise). Updated monthly.

### `GreatFirewallOfChina.p2p` — [DISCONTINUED] Comprehensive global blocklist
> **No longer updated.** Kept in the repo for archival/reference only.
>
> Previously blocked multiple threat categories:
> - All IP ranges allocated to Israel (ISP and residential)
> - Datacenter and hosting ranges used by scanners and scrapers
> - Anti-P2P monitoring organizations (MediaSentry, BayTSP, etc.)
> - Known botnet infrastructure and malicious actor ranges

## File details

| Property | Value |
|---|---|
| Format | `.p2p` — plain text, eMule/qBittorrent compatible |
| **block_only_il.p2p** | Israel ranges only (~1,599 ranges) — **actively maintained, updated monthly** |
| **GreatFirewallOfChina.p2p** | ~202,000+ ranges (comprehensive) — **discontinued, no longer updated** |
| IP source | maxmind.com's GeoLite Country + curated threat lists (historical for `GreatFirewallOfChina.p2p`) |

## How to load in qBittorrent

1. Open qBittorrent → **Preferences → Connection**
2. Under *IP Filtering*, tick **Filter path**
3. Browse and select `block_only_il.p2p`
4. Click **OK** — takes effect immediately
