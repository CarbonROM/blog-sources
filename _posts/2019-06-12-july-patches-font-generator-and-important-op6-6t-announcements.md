---
title: July Patches, Font Generator and important OP6/6T announcements
---

Hey everyone,

It's that time again. We finally wrote a new blogpost.

This time, we're going to tell you that we merged the [July Patches](https://source.android.com/security/bulletin/pixel/2019-06-01.html) in both, Oreo and Pie. The respectives branches are android-8.1.0_r65 and android-9.0.0_r40.

Next up, the [CarbonROM Font Generator](https://fonts.carbonrom.org). Have you ever missed those Microsoft Paint days where you'd create the sickest graphics with Comic Sans MS? Were you sad that we can't include that because of Licensing on Redistribution? Well worry no longer! You can now upload any TTF or OTF file of your desire and generate an resource APK out of it to use on most ROMs that feature the DU Font Engine. There are no limits. Just remember how to get back to the font chooser in case you decide to give Webdings a try ;)

Last but not least an important announcement for all OnePlus 6 and 6T users. Tomorrow's builds include some changes to the way NFC works in order to fix some issues with e.g. Google Pay. However, this is not compatible with the previous implementation, which means that you need to manually wipe the NFC data. You can do so by going to TWRP and deleting `/data/nfc`. Don't worry, if you only delete that folder none if your data will be lost and NFC will work flawless after a reboot. Until you do that however, NFC will not work, so make sure to do that.

We're currently all working hard on new features and are still finishing up some new devices that are due to join soon.

Let us know what you think about the Font Generator!
Happy Flashing/Fonting :P