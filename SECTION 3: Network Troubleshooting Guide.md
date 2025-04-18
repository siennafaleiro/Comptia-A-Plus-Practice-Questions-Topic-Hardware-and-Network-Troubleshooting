Common Network Issues:

| Issue                 | Symptoms                          | Troubleshooting                             |
|----------------------|-----------------------------------|--------------------------------------------- |
| No Connectivity      | No IP, no ping, no internet       | Check link light, IP config, cables         |
| Intermittent Connection | Drops frequently                | Check signal interference, replace cables   |
| IP Conflict          | Static IP duplicates              | Use DHCP, assign unique IPs                 |
| Slow Network         | High latency, slow load           | Ping test, check bandwidth usage            |
| DNS Issues           | Can’t resolve domain names        | Flush DNS, change DNS server                |

**Troubleshooting Commands (Windows CMD):**

- ipconfig /all: View IP config
- ipconfig /release + ipconfig /renew: Reset IP
- ping [IP/domain]: Test reachability
- tracert [domain]: Trace route to destination
- nslookup [domain]: Check DNS resolution
- netstat -an: Show open ports and connections

**Network Tools:**

- Cable Tester: Check for wiring faults
- Wi-Fi Analyzer: Identify signal issues
- Toner Probe: Trace network cables
- Protocol Analyzer (Wireshark): View packets and protocols
