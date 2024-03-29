# Testing VPS network performance

Init:
```sh
wget freevps.us/downloads/bench.sh -O - -o /dev/null|bash
```
### ServerSP
- 1 core / 1 GB RAM / 25 GB SSD
```

System Info
-----------
Processor       : QEMU Virtual CPU version 2.5+
CPU Cores       : 1
Frequency       : 2395.504 MHz
Memory          : 992 MB
Swap            :  MB
Uptime          : 43 min,

OS              : Ubuntu 16.04.6 LTS
Arch            : x86_64 (64 Bit)
Kernel          : 4.4.0-21-generic
Hostname        : xxx.xx.us


Speedtest (IPv4 only)
---------------------
Your public IPv4 is 144.217.xx.xx

Location                Provider        Speed
CDN                     Cachefly        35.1MB/s

Atlanta, GA, US         Coloat          2.80MB/s
Dallas, TX, US          Softlayer       5.39MB/s
Seattle, WA, US         Softlayer       2.45MB/s
San Jose, CA, US        Softlayer       2.81MB/s
Washington, DC, US      Softlayer       3.98MB/s

Tokyo, Japan            Linode
Singapore               Softlayer       1.01MB/s

Rotterdam, Netherlands  id3.net         1.79MB/s
Haarlem, Netherlands    Leaseweb        1.77MB/s


Disk Speed
----------
I/O (1st run)   : 1.1 GB/s
I/O (2nd run)   : 1.4 GB/s
I/O (3rd run)   : 983 MB/s
Average I/O     : 328.5 MB/s

```


### Locaweb
- 2 core / 1 GB RAM / 40 GB SSD
```

System Info
-----------
Processor       : Intel(R) Xeon(R) CPU E5-2630 v4 @ 2.20GHz
CPU Cores       : 2
Frequency       : 2200.002 MHz
Memory          : 974 MB
Swap            :  MB
Uptime          : 40 min,

OS              : Ubuntu 16.04.6 LTS
Arch            : x86_64 (64 Bit)
Kernel          : 4.4.0-139-generic
Hostname        : xx.xx.com.br


Speedtest (IPv4 only)
---------------------
Your public IPv4 is 191.252.xxx.xx

Location                Provider        Speed
CDN                     Cachefly        81.8MB/s

Atlanta, GA, US         Coloat          1.29MB/s
Dallas, TX, US          Softlayer       2.78MB/s
Seattle, WA, US         Softlayer       3.10MB/s
San Jose, CA, US        Softlayer       2.79MB/s
Washington, DC, US      Softlayer       4.66MB/s

Tokyo, Japan            Linode
Singapore               Softlayer       1.19MB/s

Rotterdam, Netherlands  id3.net         3.50MB/s
Haarlem, Netherlands    Leaseweb        4.01MB/s


Disk Speed
----------
I/O (1st run)   : 26.0 MB/s
I/O (2nd run)   : 26.9 MB/s
I/O (3rd run)   : 24.2 MB/s
Average I/O     : 25.7 MB/s

```

### Hostinger
- 1 core / 1 GB RAM / 20 GB SSD

```
System Info
-----------
Processor       : Intel(R) Xeon(R) Silver 4114 CPU @ 2.20GHz
CPU Cores       : 2
Frequency       : 1210.120 MHz
Memory          : 1024 MB
Swap            :  MB
Uptime          : 18 min,

OS              : Ubuntu 16.04.6 LTS
Arch            : x86_64 (64 Bit)
Kernel          : 4.4.0
Hostname        : xxx.local


Speedtest (IPv4 only)
---------------------
Your public IPv4 is 31.220.xx.x

Location                Provider        Speed
CDN                     Cachefly        62.0MB/s

Atlanta, GA, US         Coloat          26.8MB/s
Dallas, TX, US          Softlayer       14.5MB/s
Seattle, WA, US         Softlayer       2.28MB/s
San Jose, CA, US        Softlayer       2.58MB/s
Washington, DC, US      Softlayer       11.6MB/s

Tokyo, Japan            Linode
Singapore               Softlayer       4.25MB/s

Rotterdam, Netherlands  id3.net         4.02MB/s
Haarlem, Netherlands    Leaseweb        10.3MB/s


Disk Speed
----------
I/O (1st run)   : 208 MB/s
I/O (2nd run)   : 107 MB/s
I/O (3rd run)   : 109 MB/s
Average I/O     : 141.333 MB/s

```
