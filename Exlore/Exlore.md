![alt](https://github.com/haojames/HackTheBox/blob/main/Exlore/image/Challenge.PNG)

# Analysis
	Use __nmap__ check ports using in target.
> nmap -p- -v  10.10.10.247

After using, we give 4 ports in target.

![alt](https://github.com/haojames/HackTheBox/blob/main/Exlore/image/NMAP_CHECK_PORT.PNG)

Port **2222**: ConnectSSH.

Port **5555**: Android Debug Bridge (ADB).

> https://www.trendmicro.com/en_us/research/18/g/open-adb-ports-being-exploited-to-spread-possible-satori-variant-in-android-devices.html

Port **42135**: https://www.speedguide.net/port.php?port=42135 .
Port **59777**: ES File Explorer File Manager application for Android.
Port **45181**: https://www.speedguide.net/port.php?port=45181 .