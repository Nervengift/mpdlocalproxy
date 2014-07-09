mpdlocalproxy
=============

Takes a list of mpd servers and relays all clients to the first available one of them. This allows all clients to automatically connect to another server when the computer moves to another network.


Installation & use
==================

By now, the servers are hardcoded, you have to change them in the source file.

Only needs python 3. Just run it.

	./mpdlocalproxy

Then configure your clients to point to loacalhost port 6601.
