# openclaw-companion

Android MVP test build for discovering OpenClaw gateways on the local network and viewing sessions from the selected gateway.

## Files

- `app-debug.apk` — latest debug build
- `0.1.0-app-debug.apk` — initial build
- `0.1.1-app-debug.apk` — permission/auth/safe-area/manual-gateway fixes
- `0.1.2-app-debug.apk` — scrolling fix + cleartext LAN gateway access fix
- `SHA256SUMS.txt` — checksums

## MVP scope

- Discover `_openclaw-gw._tcp.` gateways on LAN
- Show discovered gateways
- Switch between multiple gateways
- Connect to the selected gateway
- Fetch and display `sessions.list`
- Manual gateway entry (host/port/TLS)
- Runtime discovery permission prompt
- Safe-area aware top layout for status bar / camera cutout
- Full-screen vertical scrolling
- Cleartext LAN gateway access enabled for local HTTP/WS gateways
