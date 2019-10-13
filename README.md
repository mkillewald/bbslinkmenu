# C-Net BBSLink Menu 1.0.1 (devel version)

A C-Net Pfile used to easily add all BBSLink.net games, leaderboards, grafitti wall and BBS List to your system.
http://www.bbslink.net/

**************************************************************************

### Changelog

v1.0.0 (21 Sep 2019) by k1ds3ns4t10n of -X-caliber BBS

This is public domain software. Use at your own risk.
**************************************************************************

### Installation Instructions:

1. Create a folder called 'BBSLink' in your PFiles: directory, and
copy the files bbslinkmenu, menuGame.ans, and menuScore.ans there.

2. Install bbslinkconnect and any enabled modules (i.e bbslinkwall,
bbslinklist, or bbslinkscore) in the same folder from step 1.
https://aminet.net/package/comm/cnet/bbslinkconnect

NOTE: By default, all modules are enabled in the "SysOp
Configurable Options" block.

optional modules:
  https://aminet.net/package/comm/cnet/bbslinkwl20
  https://aminet.net/package/comm/cnet/bbslinklist
  https://aminet.net/package/comm/cnet/bbslinkscore

3. If you haven't already, download http_get from Aminet and install
in C: (needed for bbslinkwall, bbslinklist, and bbslinkscore)
https://aminet.net/package/comm/tcp/http_get

4. Customize the Game and Score menus as needed. See "Game Menu
Configuration" and "Score Menu Coniguration" blocks.

5. Add this file as an Arexx executable anywhere on your system using
the path:

pfiles:bbslink/bbslinkmenu

6. That's it!

**************************************************************************
### -X-caliber BBS telnet://bbs.aholix.net:6800
