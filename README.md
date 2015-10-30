YeloTV profile for plex
-----------------------

### Info
`https://forums.plex.tv/discussion/73702/writing-profiles-for-dlna-devices`

### Install
- `$ cd /Users/ilja/Library/Application Support/Plex Media Server`
- `$ mkdir Profiles`
- copy yelotv.xml to this directory
- restart Plex Media Server

### Debug

`tail -f ~/Library/Logs/Plex\ DLNA\ Server.log`

```
Sep 22, 2015 14:14:55 [0x7fff789de300] DEBUG - Unique device name = 7d6a3b80-37ae-e6da-6710-5dab3c266378
Sep 22, 2015 14:14:55 [0x7fff789de300] DEBUG - DLNA server port: 32469
Sep 22, 2015 14:14:55 [0x7fff789de300] DEBUG - PMS: http://127.0.0.1:32400/
Sep 22, 2015 14:14:55 [0x7fff789de300] DEBUG - MyPlex: https://plex.tv/
Sep 22, 2015 14:14:55 [0x7fff789de300] DEBUG - [PERF] Slowest TransactionScope in 10.000000 ms.
Sep 22, 2015 14:14:56 [0x7fff789de300] DEBUG - Reading system DLNA client profiles
Sep 22, 2015 14:14:56 [0x7fff789de300] DEBUG - Reading user client profile yelotv
Sep 22, 2015 14:14:56 [0x7fff789de300] DEBUG - Read 20 DLNA client profiles
Sep 22, 2015 14:14:56 [0x7fff789de300] DEBUG - DLNA device discovery enabled every 60 seconds
Sep 22, 2015 14:14:56 [0x7fff789de300] DEBUG - Initialization complete
```