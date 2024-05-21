# Hackintoshery
Half-assed "guides" &amp; Resources for my own reference...but maybe it'll help someone else too. 


## AMFIPass
This is needed for Adobe CC and likely some other apps too. 

1. Add AMFIPass.kext to your "/EFI/OC/Kexts"
2. Rebuild config.plist to load the kext (I used Open Core Auxiliary Tools)
3. Change some boot args. Add "-amfipassbeta" and if you have "amfi=0x80" then remove it. 
4. Reboot
5. Profit!

