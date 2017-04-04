# statelesshttpd
Experimental TCP/IP stack with completely stateless web server.

Inspired by challenges I'd encountered in my first proper job, in 2004 I decided to write an extremely primitive TCP/IP stack and web server for simple read-only embedded applications.  I kept the "file" number and offset in the sequence number so that the client would be forced to maintain it on my behalf and then responded to every packet as it appeared, regardless of whether or not it was part of an established TCP link.

I'll upload it after I've managed to test it.  It needs porting from another OS.
