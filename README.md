# VPN Gate Tester

Node.js 18+ required.

## Run locally
```bash
npm install
npm start
```
Open http://localhost:3000. For iPhone Safari on the same Wi-Fi, open the computer's LAN IP and port 3000.

## Included
- VPN Gate public API CSV retrieval
- Country filtering and sorting by official fields
- Server-side TCP connect-time checks (up to 80 nodes)
- OpenVPN profile export

## Measurement limits
TCP connect time is measured from the server hosting this app, not from your iPhone. It is not ICMP ping and not VPN tunnel latency. Official Mbps/Ping are provider-reported values. Measuring actual iPhone VPN tunnel throughput requires a native VPN client or a separate device-side test; a normal webpage cannot control iOS VPN tunnels.
