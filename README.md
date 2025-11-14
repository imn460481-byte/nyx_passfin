# nyx_passfin

# wifi-passive-scanner

Passive Wi-Fi scanner for ethical auditing and lab use.

## Purpose
- Passively collects broadcast Wi-Fi info (SSID, BSSID, channel, signal, security).
- Safe for learning and permitted auditing; **do not use to attack networks**.

## Quickstart
1. Clone repo
2. Open in GitHub Codespaces or run locally on Linux
3. Ensure `nmcli` is installed (`sudo apt install network-manager`)
4. Run: `python3 wifi_scanner.py --interval 10 --out csv --file results.csv`

## Storage
- CSV or SQLite options available.
- Use results to analyze signal patterns, map channels, or create visualizations.

## License
MIT
