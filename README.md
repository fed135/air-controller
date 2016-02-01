# air-controller
A generic air-controller boilerplate

[ In Progress ]

I wanted to grab the -very- crude code from the air-controller app I made for Global Game Jam 2016 and make something more generic and easy to use - in case I want to make another similar app.

I also want to add/fix the following:

- Allow multiple simultaneous lobbies (named with optional password fields)
- Streamline socket communications
- Config-driven events and state-machines
- Can create input zones and bind them to listeners
- Dynamic Sections + plug-in a front-end framework (RequireJS + WebComponents)
- Loading screens/asset preloading
- App manifest (Standalone apps)
- MSGPack/JSON option
- Can broadcast events as web-sockets, tcp or udp
- Manage idle/dead connections (browser visibility)
- Full accelerometer support
- Cleaner logging. [debug](https://www.npmjs.com/package/debug) for server and [Logger](https://github.com/fed135/logrunner) for client
