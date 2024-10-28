+++
title = "Porting a Unity game from Windows to iOS: a complicated process"
date = 2024-10-03T15:42:34+02:00
slug = ""
authors = ["isaac"]
tags = ["homework"]
categories = ["homework2"]
externalLink = ""
series = []
+++

I would like to preface this article with its outcome: I did not manage to make this work. I finished the lab with a classmate who has a Mac. However, if you have a Windows PC and an iPhone, like me, then you may want to check out what I tried (to no avail).

## Installation challenges

I had a feeling trying to get Unity working on my 6-year-old iPhone XR using Windows 11 might not be easy. 

I managed to install Unity Remote 5 on my phone and set Unity to build for iOS, but Unity just couldn’t detect my phone, since my iPhone doesn’t have a "developer mode", possibly due to the OS version. 

I tried installing iTunes, which is supposed to [bridge the connection between iOS devices and Windows](https://discussions.unity.com/t/cant-connect-to-iphone-via-unity-5-remote-with-usb-3-0-ports/172452/3), but even though iTunes picked up my phone, Unity didn’t budge.

Next, I tried creating an Apple Developer account, only to find out that adding a trusted device requires a paid subscription--which I was not going to pay for.

## The simple fix I didn’t see coming

Finally, I restarted my computer, and suddenly my phone appeared in Unity's device list! Honestly, this made me rethink my assumption that this setup was doomed to fail from the start. I’ve gotten so used to expecting errors when I code that I almost _brace myself for things to go wrong_. While that mindset has its benefits (fewer surprises when things don't work), I realized that maybe being a bit more optimistic can help too.

## And then... it stopped working again

After a brief success, I encountered another road block. This time, everything was detecting my phone, but when I tried to run the game, it only showed up on my computer screen—not on my phone. I ended up pairing up with a classmate who uses a Mac and iPhone, which worked seamlessly with iOS, unlike my Windows setup.

This experience was a reminder of just how tricky it can be to make Windows and iOS work together for development. In the future, using a Mac for iOS projects might save some hassle. For now, I’ll keep experimenting with different fixes—and when in doubt, teamwork with Mac users is always an option!