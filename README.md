# PyNetScripts

Works on the Windows Subsystem Linux and Linux.

Run `./configure` to install the dependencies. Python >= 3.6 required.

## pynmap

Uses `fping` to ping a range of address on a local network.

Call it using `./pynmap IPv4/mask`, it will print all the pingable ip adresses detected, one after another.

## monitor-bw

Uses scapy to sniff the network, and a modified version of texttable (to handle ansi escape chars) for rendering.

A bandwith usage per IP monitor program.