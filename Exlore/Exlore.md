![alt](https://github.com/haojames/HackTheBox/blob/main/Exlore/image/Challenge.PNG)

# Analysis
	Use __nmap__ check ports using in target.
> nmap -p- -v  10.10.10.247

After using, we give 4 ports in target.

![alt](https://github.com/haojames/HackTheBox/blob/main/Exlore/image/NMAP_CHECK_PORT.PNG)


Port **2222**: ConnectSSH.
Port **5555**: Android Debug Bridge (ADB).
Port **42135**: X.
Port **59777**: ES File Explorer File Manager application for Android.
Port **45181**: X.