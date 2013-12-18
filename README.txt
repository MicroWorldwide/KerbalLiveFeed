KerbalLiveFeed Plugin, Client, and Server v0.7.3
Created by Alfred Lam


# Installation

* Place KLFClient.exe in your KSP install folder.
* Place KLF folder in your GameData folder.



# How to use

* Run KLFClient.exe while KSP is running and connect to a KLF server.



# Server Settings

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

    The maximum height of the screenshots players share.  Between 135 to 540.
    
    (Ideal values: 135, 144, 180, 270, 315, 360, 540)



# Recent Changes

* 2013-12-18 Compatibility for KSP 0.23, version to 0.7.3



# Project Contributors

* Originally created by Alfred Lam
* raad287 (nevermoto)
* Worrom36
* Cobryis
* Digiex
* voneiden
* descention
* velusip
* nobleleader13245
