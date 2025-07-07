# Snapchat & TikTok Blocklist for Pi-hole

This blocklist is designed to **block Snapchat and TikTok** at the DNS level using Pi-hole. It targets core domains required for app and web access, making it effective for parental controls or productivity.

## Usage

1. Download or copy `blocklist.txt` from this repository.
2. In your Pi-hole admin panel, go to **Group Management > Adlists**.
3. Add the raw GitHub URL of `blocklist.txt` or upload it directly.
4. Update Pi-hole gravity to apply the blocklist.

> **Note:** Blocking these domains may also affect some third-party services or content delivery networks used by other apps. Test thoroughly on your network.

## Sources

- Community blocklists and expert recommendations from Reddit, GitHub, and security forums.
- Manually curated for maximum coverage and minimal false positives.

## Disclaimer

Use at your own risk. Blocking these domains will disrupt Snapchat and TikTok functionality across your network.
