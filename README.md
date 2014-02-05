node-sonos-discovery
====================

This is a simplification of the Sonos implementation of UPnP for the node.js stack. This library will allow you to interact with your sonos system with simple commands like play, pause, next etc, but is expected to be ran at all times because it keeps track of the players.

0.9.0 is totally rewritten with another XML parser. This might break things. I've also added better subscription handling, according to the specification.

For example integrations, please see the following projects:

https://github.com/jishi/node-sonos-http-api
https://github.com/jishi/node-sonos-web-controller