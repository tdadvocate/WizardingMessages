# WizardingMessages
A bug found in the Messages app on all devices from at least iOS 12.1-12.3.1 (and somewhat iOS 13) using a link from the App Store.

# Explanation
Sharing the link below that is gathered from the official Apple App Store may cause the Messages app of a user's device to react in unexpected ways. This includes crashing, data loss, and possibly more oddities. The link in question is for Niantic Labs' popular app Harry Potter: Wizards Unite. For whatever reason the App Store creates a link that is unable to be properly handled by devices on at least the above listed firmwares. It appears that iOS 12.4 finally may fix the issue for public iOS builds. iOS 13 appears to handle this link differently and only has minor bugginess with it where sometimes the messages will just fail to load properly but will not crash the app or seemingly cause any data loss.

# Link
https://apps.apple.com/us/app/harry-potter-wizards-unite/id1452352832

# Crash Logs
Below are 2 links to crash logs from a jailbroken iOS 12.1 iPhone SE running Unc0ver 3.2.x and grabbed through CrashReporter as it does not always trigger the log creation in Cr4shed. I will be turning these into files that will be located within this repo later. <br/>
https://pastebin.com/z9jsldqc <br/>
https://pastebin.com/kjmfsvuq

# Help
If you have anything else that you can add to this repo, please feel free to send pull and merge requests. I will happily take a look and add any additional information to this repo with credit to you here so it is easily visible for even the newest of github users. 

# License
This is temporarily in the read me until I can get it to upload to the repo properly on a different network. Idk why I can't seem to upload a 4kb file right now but oh well.

Creative Courtesy License
Version 0.0.3, February 2019
Copyright 2019 Wavelink Studios

With this license, the person looking at this source (henceforth referred to as 'you'), may not just copy and paste the work of any developer licensing their software with the Creative Courtesy License. You are welcome to make forks of these projects with a few rules surrounding this work (See Section I). The developer using this license is protected from any liability during use of this source in any capacity (See Section II). And the releasing of unmodified projects is prohibited (See Section III)

Section I - Forking
1)You may not just copy and paste the work of any developer using this license. 
a)This includes any of the developers of this fork may or may not have been created by.
2)You must also make sure to credit any and all developers related to this project.
a)i.e.: If you are forking this and it is a fork of a fork of the main project, you must credit the original developer as well as the 2 developers that have forked up to the point you are using.
3)Forks you create must have some kind of bug fixes, additional content, or elsewise added in before releasing anything using this source. 
a)Moving the location of code around within itself does not fall under this rule and is subject to enforcement of punishment for violating this license.
b)See also Section III for more rules refarding releases. 

Section II - Source Developer(s) Liabilities
1)The developer(s) who have worked on this source up to this current fork are completely waived of any liability for damages or issues caused by this source in any way
a)This is including, but not limited to; using this source as is, attempting to modify the source, and from any modifications not by the original developer(s) 
2)This source is not guaranteed to have been validated for functionality and may be completely unfunctional at this time. 

Section III - Releases
1)Any attempts to release projects using unmodified code without express consent of the developer(s) is not allowed
a)This includes, but is not limited to; releasing exact copies of the code within this project, compiling this code with only minor naming changes to attempt to hide original ownership, compiling the code as is, etc. 
