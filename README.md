truckputer
==========

Intended to ship on a Raspberry Pi device to constantly monitor bluetooth connections to an OOBDII interface.  If it can connect it will automatically log all OOBDII data internally.  It will also constantly monitor WiFi and if it can connect it will push up an HTTP daemon, and upload data to a known database endpoint on a server.

Implementation will be done in NodeJS, using mostly existing libraries.


