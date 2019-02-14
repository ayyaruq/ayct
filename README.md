# AyCT
A network parser for FFXIV that ships data to nowhere in particular right now. All
packet capture is done by [Zanarkand](https://github.com/ayyaruq/zanarkand).

AyCT parses traffic between the FFXIV servers and where the parser is installed,
regardless of PC or console platforms. For each message read, an event is dispatched
to parser routines, events are correlated, and then published to various exporters
such as a live dashboard via WebSocket in, or archived to a database for later analysis.

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
- [ ] Ant Design's Alain framework, composable widgets with a nice default?
- [ ] AyCT configuration
- [ ] Latency graph/counter
- [ ] Eorzean/Server time
- [ ] Battle - standard parsing stuff, in theory socket can be used for overlays
- [ ] Nerd - raw events data/files
- [ ] Triggers - flash on received events or export to TTS

### Far Future Roadmap
- [ ] generic loot parsing (drop rates by instance)
- [ ] name reconciliation
- [ ] gear reconciliation
- [ ] export fishing and hunt data
- [ ] export item drop rate data (desynth, treasure, chests)
- [ ] export inventory data

### Development Roadmap
- [ ] generic plugin interface
- [ ] parsers as plugins
- [ ] exporters directly in the dashboard
- [ ] dynamic parser IPC updates

### Bugs and Feature Requests
Please open an issue on GitHub, or message @acchan#4976 on Discord.

### Contributing
pls no
