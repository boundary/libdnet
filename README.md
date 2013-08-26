
libdnet
-------

libdnet provides a simplified, portable interface to several low-level
networking routines, including network address manipulation, kernel
arp(4) cache and route(4) table lookup and manipulation, network
firewalling, network interface lookup and manipulation, IP tunnelling,
and raw IP packet and Ethernet frame transmission.

WWW: http://code.google.com/p/libdnet/

boundary/libdnet
----------------
    * merged fixes and features from nmap fork of libdnet-stripped
        https://github.com/nmap/nmap/tree/master/libdnet-stripped
    * merged fixes from https://code.google.com/p/libdnet/issues/list
    * mingw build compatiblity
    * added os_intf_name and pcap_intf_name attributes
    * to intf.h for gaining access to the raw windows interface names
    * adds htonll/ntohll 64-bit endian conversions
    * various small build fixes

