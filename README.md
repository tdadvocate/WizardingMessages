# WizardingMessages
A bug found in the Messages app on all devices from at least iOS 12.1-12.3.1 (and somewhat iOS 13) using a link from the App Store.

#Explanation
Sharing the link below that is gathered from the official Apple App Store may cause the Messages app of a user's device to react in unexpected ways. This includes crashing, data loss, and possibly more oddities. The link in question is for Niantic Labs' popular app Harry Potter: Wizards Unite. For whatever reason the App Store creates a link that is unable to be properly handled by devices on at least the above listed firmwares. It appears that iOS 12.4 finally may fix the issue for public iOS builds. iOS 13 appears to handle this link differently and only has minor bugginess with it where sometimes the messages will just fail to load properly but will not crash the app or seemingly cause any data loss.

#Link
https://apps.apple.com/us/app/harry-potter-wizards-unite/id1452352832

#Crash Logs
Below are 2 links to crash logs from a jailbroken iOS 12.1 iPhone SE running Unc0ver 3.2.x and grabbed through CrashReporter as it does not always trigger the log creation in Cr4shed. I will be turning these into files that will be located within this repo later.
https://pastebin.com/z9jsldqc
https://pastebin.com/kjmfsvuq

#Help
If you have anything else that you can add to this repo, please feel free to send pull and merge requests. I will happily take a look and add any additional information to this repo with credit to you here so it is easily visible for even the newest of github users. 
