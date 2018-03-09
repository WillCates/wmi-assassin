# wmi-assassin
Kills those pesky WMI objects


This is the script I have used to eradicate a WMI object infection. It was an infection caused by a crypto miner worm, stored payload, automated job and propagation techniques in wmi objects.

You WILL need to ensure that the filter strings are correct for your particular infection - they are not all the same. THis is just a nifty way to kill it using impacket. I suck at windows, so its always easier for me to script something in linux.

Reference this ESET/Spiceworks post, as well:

https://community.spiceworks.com/topic/2080003-malicious-powershell-script-causing-100-cpu-load-solved?page=1#entry-7336947

Dependencies:

1. Impacket: https://github.com/CoreSecurity/impacket (For logging in via WMI > cmd.exe > wmic delete)

2. ESET Script to ID infection (Optional but recommended), check this post: https://forum.eset.com/topic/14143-powershell-script-100-cpu-load-malicious-attack/

