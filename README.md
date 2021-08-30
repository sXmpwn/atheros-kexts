# atheros
Kexts for many Atheros chipsets working on macOS High Sierra, Mojave, Catalina and Big Sur

## Supported Devices

- AR9281
- AR5418/5133
- AR9280 
- AR9380
- AR94621
- AR9283
- AR9285
- AR9287
- AR94851

## Installation
### OpenCore
Download those 2 Kexts, "AirPortAtheros40.kext" and "HS80211Family.kext", put these into EFI/OC/Kexts, add them into your config.plist or do an OC Snapshot if you’re using ProperTree. 

Make sure that "HS80211Family.kext" is loading first and that "AirPortAtheros40.kext" is loading after it in the config.plist. 

It should look exactly like this:

![Example](https://user-images.githubusercontent.com/73723350/131271107-abe28193-fd69-4ad6-ab0c-51a306b68928.png)


### Clover 
Download those 2 Kexts, "AirPortAtheros40.kext" and "HS80211Family.kext", put these into CLOVER/Kexts/Other.
