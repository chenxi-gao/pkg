# openclaw-companion

Android MVP test build for discovering OpenClaw gateways on the local network and viewing sessions from the selected gateway.

## Files

- `app-debug.apk` — latest debug build
- `0.1.0-app-debug.apk` — initial build
- `0.1.1-app-debug.apk` — build with permission/auth/safe-area/manual-gateway fixes
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
