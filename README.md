<small id='version'>v0.0.2</small>
<!--
@author: GFI
FHAG
-->
<h1 id='raspiid' style='color:DodgerBlue'><b>Identify your Raspberry</b></h1>
---

<h2 id='id' style='color:DodgerBlue'><b>id.py</b></h2>

Identify your Raspberry and show all key information on screen. Save the same information in file `id.txt` .

**Installation**

Download `id.py` into the  directory where you need it.

**How to use**

from commandline: `$ python3 id.py`

or add to crontab to run at startup
```bash
crontab:
...
# m h  dom mon dow   command
@reboot python3.7 id.py
```
**Sample output**

```
 $ python3 id.py
---------------------------- Welcome to 'raspi41GB' ----------------------------
Computer Model     : Raspberry Pi 4 Model B 1GB
Total memory       : 1GB
Disk Space         : total=12GB used= 68% free=4GB
Model              : Raspberry Pi 4 Model B Rev 1.1
Processorname      : ARMv7 Processor rev 3 (v7l) 7.3
Hardware - Revision: BCM2835 - a03111
# of CPUs          : - [4]
CPU frequency      : 1,500Mhz
BogoMIPs/CPU       : 270.00
CPU serial         : 100000003408c4cb
System             : Linux#1294 SMP Thu Jan 30 13:21:14 GMT 2020
Machine            : armv7l
Processor          : 
Pretty Name        : Raspbian GNU/Linux 10 (buster)"
Home URL           : http://www.raspbian.org/"
Support URL        : http://www.raspbian.org/RaspbianForums"
Platform           : linux 10.3
Python version     : 3.7.3 (default, Dec 20 2019, 18:57:59)  [GCC 8.3.0]
Active Connections
- lo               : 127.0.0.1
- eth0             : 192.168.0.235
------------------- id.py 0.1.4 -- Fri Apr 10 17:24:52 2020 --------------------
```

<a href='#raspiinfo'>return to top</a>

---
