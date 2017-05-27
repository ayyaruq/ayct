# AyCT
A network parser for FFXIV that ships data to nowhere in particular right now.

AyCT parses traffic between the FFXIV servers and where the parser is installed,
regardless of PC or console platforms. For each message read, an event is dispatched
to various parser, which can then be accessed over a websocket in a live dashboard in
pseudo-realtime, and archived to a database for later analysis. Ad-hoc queries and
comparisons over time are simple to do via the dashboard if using an appropriate
database backend.

Triggers, realtime meters, and one-click exports to FFLogs, FF14Angler, and
FFXIV the Hunt are planned.

### Roadmap
- [ ] combat log parsing
- [ ] fishing parsing
- [ ] desynthesis parsing (item drops)
- [ ] treasure hunt parsing (chest drops)
- [ ] web dashboard and configuration

### Far Future Roadmap
- [ ] generic loot parsing (drop rates by instance)
- [ ] name reconciliation
- [ ] triggers dashboard
- [ ] export fishing and hunt data
- [ ] export item drop rate data

### Bugs and Feature Requests
Please open an issue on GitHub, or find @acchan#4976 in The Balance on Discord.

### Contributing
pls no
