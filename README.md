# Kerbal LiveFeed

Plugin, Client, and Server created by Alfred Lam (C) GNU GPLv3

## Installation

* The KLFClient must be installed into the root KSP directory.

> KLFClient.exe
> KLFClientConfig.xml

* Place the "KLF" folder in your GameData/ folder.



## Usage

* Run KLFClient.exe
* Configure a username and server, and use /connect
* Start KSP

_MacOS/Linux users should open a terminal window and run the following:_

    TERM=ansi; mono KLFClient.exe



## Troubleshooting

*  KLF Window missing in-game!

   * Make sure the Plugin resides within the GameData directory:

     >     GameData/KLF/Plugins/KerbalLiveFeed.dll

*  Random text and symbols instead of colour output in KLFClient.exe

   * Before running the client, set the TERM environment variable to ansi:

     >     TERM=ansi; mono KLFClient.exe


## Server Settings

* joinMessage

    Shown to players when they join the server

* updatesPerSecond

    The number of updates that will be received from all clients combined per
    second.  The higher you set this number, the more frequently clients will
    send updates.  As the number of active clients increases, the frequency of
    updates will decrease to not exceed this many updates per second.

* totalInactiveShips

    The maximum number of inactive ships that will be sent from all clients
    combined.  The higher you set this number, the more inactive ships will be
    seen by clients.  As the number of clients in-flight increases, the number
    of inactive ships sent per-client will decrease to not exceed this total.

    If the number of clients in-flight exceeds this number, no inactive ships
    will be sent.
	
* screenshotInterval

    The minimum time a client must wait after sharing a screenshot before they
    can share another.

* autoRestart

    If true, the server will attempt to restart after catching an unhandled
    exception.

* saveScreenshots

    If true, the server will save all screenshots to the klfScreenshots folder.

* screenshotHeight

    The maximum height of the screenshots players share.  Between 135 to 600.
    
    (Ideal values: 135, 144, 180, 270, 315, 360, 540)


## Project Contributors

* Alfred Lam (Original creator and license holder)
* raad287 (nevermoto)
* Worrom36
* Cobryis
* Digiex
* voneiden
* descention
* velusip
* nobleleader13245
* Stavell

