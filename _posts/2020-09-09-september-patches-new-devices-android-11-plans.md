---
title: September Patches, new devices, Android 11 Plans
mathjax: true
layout: post
---

Now that Android 11 is released and you slowly but steadily realise that it will take at least a few months until Android 11 custom ROMs are coming to your device we are here to cheer you up with news. Big ones this time, if we may say so.

First of, the good news. We added new devices and other devices have been upgrade to CR-8.0 coming from CR-7.0.

**New in CR-8.0:**
* [OnePlus 7 (guacamoleb)](https://get.carbonrom.org/device-guacamoleb.html)
* [OnePlus 7T Pro (hotdog)](https://get.carbonrom.org/device-hotdog.html)
* [OnePlus 7T Pro 5G (hotdogg)](https://get.carbonrom.org/device-hotdogg.html)

**Upgraded from CR-7.0:**
* [Xiaomi Redmi Note 4 (mido)](https://get.carbonrom.org/device-mido.html)

Sadly, due to absolutely unaccepable behaviour by a former team member we also had to disable two devices due to a now lack of maintainer.
For now the devices have been disabled and will stay disabled until a maintainer steps up. There's already some devs showing interest in following up but that will probably take a while to settle in.

**Disabled devices:**
* Xiaomi Redmi Note 7 (lavender)
* Xiaomi Redmi 7 (onclite)

We're sorry for the inconvenince but the behaviour and views of said maintainer were inacceptable and hurt other members of the community which is inacceptable to us.

Thats not it just yet though. We've been working hard in the past week and introduced a bunch of heavy improvements to the ROM itself. Usually this kind of post would begin by explaining how we merged the [Android Security Patches for September](https://source.android.com/security/bulletin/2020-09-01). Unfortunately, these have not been released yet, but rest assured they will be merged once released though. That also means that the currently merged Android Security Patch on both CR-7.0 and CR-8.0 is [August](https://source.android.com/security/bulletin/2020-08-01).

In addition to that, we have merged various improvements. Better organisation inside CarbonFibers and Settings, fixed a few Search related issues and introduced design improvements to the lockscreen clocks to unify them in look and behaviour. In earlier builds we also introduced the long requested VoLTE and VoWiFi icons that can be enabled inside CarbonFibers.

The most noticible improvement however should be changes to the font engine. We reworked the way fonts get applied to make it work with USAP Pooling. USAP Pooling is a process to improve app startup times enabled on some devices (e.G. The OnePlus 7 family). However, during the rework we also improved font applying for devices without USAP pooling which, during our tests, resulted in improved app launch times of up to 25%. With the usage of USAP Pools that went as high as 35% compared to the old font implementation without the usage of USAP pools.

TL;DR: It's fast now. Very fast.

There's still a few things planned for CR-8.0 and we're far away from dropping support on it anytime soon. However, as always with a new Android release available, things might be a little slower now that the team is working on Android 11 bringup. Stay tuned!

As always, we'd like to end with a warm welcome to new users and devices and happy flashing to all of you!