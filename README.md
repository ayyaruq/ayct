# AyCT
A network parser for FFXIV that ships data to nowhere in particular right now. All
packet capture is done by [Zanarkand](https://github.com/ayyaruq/zanarkand).

AyCT parses traffic between the FFXIV servers and where the parser is installed,
regardless of PC or console platforms. For each message read, an event is dispatched
to parser routines, and then published to external sites or databases, and optionally
an HTTP/WS router proxy for exposing on dashboards.

Triggers, realtime meters, and one-click exports to [FFLogs](https://www.fflogs.com),
[TeamCraft](https://ffxivteamcraft.com), [The Hunt](https://ffxiv-the-hunt.net),
and other services are planned.

### Parser Roadmap
- [ ] combat logs
- [x] inventory addition/removal of items
- [ ] fishing time/bait/status/weather
- [ ] desynthesis results
- [ ] treasure hunt chest drops

### Dashboard Roadmap
- [ ] AyCT configuration
- [ ] Latency graph/counter

### Plugin Dashboard Roadmap
- [ ] Battle - standard parsing stuff, in theory socket can be used for overlays
- [ ] Triggers - flash on received events or export to TTS
- [ ] Nerd - raw events data/files?

### Far Future Roadmap
- [ ] generic loot parsing (drop rates by instance)
- [ ] gear reconciliation

### Development Roadmap
- [ ] generic plugin interface
- [ ] parsers as plugins
- [ ] exporters directly in the dashboard?
- [ ] dynamic parser IPC updates
- [ ] auto-updater

### Bugs and Feature Requests
Please open an issue on GitHub, or message @acchan#5683 on Discord.

### Contributing
pls no
