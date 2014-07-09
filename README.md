mpdlocalproxy
=============

Takes a list of mpd servers and relays all clients to the first available one of them. This allows all clients to automatically connect to another server when the computer moves to another network.


Installation & use
==================

A configuration file consists of one server per line, ordered by priority and may contain ports (see config example).
Only needs python 3. Just run it.

	./mpdlocalproxy [configfile]

Then configure your clients to point to loacalhost port 6601.
