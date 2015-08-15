# nfex
Automatically exported from code.google.com/p/nfex

### Overview
nfex is a tool for extracting files from the network in real-time or post-capture from an offline tcpdump pcap savefile. It is based off of the code-base from the apparently defunct project tcpxtract.
  
nfex offers:
* Asynchronous user/event-driven interface
* Real-time or offline file extraction
* Custom written search algorithm is lightning fast and very scalable
* Search algorithm scales across packet boundaries for total coverage and forensic quality
* Support for 27 file formats
* A simple, repeatable way to add new file formats by editing the configuration file (post compilation)
* GeoIP targeting support using the free MaxMind C API
* Analysis tool for post extraction processing

#### Compilation and Installation
Build and install these fine libraries:
* libpcap
* libnet

Optionally build and install this guy:
* MaxMind GeoIP library

`./configure && make`  
`sudo make install`
