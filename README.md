# Fix-WiFi-Killer-6-AX1650
slow WiFi, Killer 6 AX1650 160MHz 200D2W

#Fix The WiFi-Killer-6-AX1650 With these commands, open powershell as administrator, copy and paste one line at a time from below, and press enter after each :

- netsh int tcp set global chimney=enabled
- netsh int tcp set global autotuninglevel=normal
- netsh int tcp set supplemental
- netsh int tcp set global dca=enabled
- netsh int tcp set global netdma=enabled
- netsh int tcp set global ecncapability=enabled
- netsh int tcp set global congestionprovider=ctcp
