+++ 
date = 2024-09-24T15:18:00+02:00
title = "Affordances, Gestalt laws, dark patterns"
description = "(Part of HCI Homework 1)"
slug = ""
authors = ["isaac"]
tags = ["homework"]
categories = ["homework1"]
externalLink = ""
series = []
+++

# Affordances

## _"What's a good affordance in your daily life?"_

A good affordance I can think of when writing this is the pretty smart system my laptop has got, which emulates a NumPad:

![asus numpad emulation](/images/asus.png)

With the touch of a button, the trackpad becomes a numpad--which is really convenient, considering the laptop is too small to have both. One minor issue is that the presence of the emulated numpad hinders the ability to use the trackpad, but they usually don't need to be used at the same time. Another issue which unfortunately really affects the UX is that to differentiate a trackpad finger tap and a numpad finger tap, one has to press the pad for a little bit longer in order to input a number. This means it can be quite tedious and slow to type numbers on that emulated numpad. Overall, it is still a smart and useful affordance in my opinion.

## _"Can you name a bad one?"_

Choosing the right temperature in my student dorm's shower is a real challenge, it has two **very** sensitive knobs for hot and cold water so the perfect temperature and pressure is practically impossible to obtain. 

![two-knob shower](/images/shower.jpg)

(my shower basically looks like this)

I grew up with these:

![better shower](/images/bettershower.jpg)

I believe having both the pressure and the temperature in one single control is much better; or at least set the pressure and the temperature on two dedicated knobs, rather than a "hot" and a "cold" one.

Studying engineering has taught me to always remember there is an engineer/a team of engineers behind each design that surrounds us. I am heavily interested in the ability to improve existing designs with clever solutions, and that is why I chose this path!


# Gestalt Laws

## _Famous grocery website I prefer not to name here_

This famous French supermarket firm lets you order your groceries online to go pick up your order at a drive-in location. 
I tried it yesterday and I must say their website is painful to use. 

The Gestalt law of proximity is one of many that is (intentionally or not) not respected on their website.

![terrible website design](/images/carrefour.png)

Above is my recreation of what I saw yesterday. _Does the discount progress bar apply to the product above it or below?_ It would be way more legible had the progress bars been moved closer to the appropriate products. Considering how many bad design decisions were on that website, I have a feeling (some of) it is intentional, meaning this website would also deserve to be part of the "dark patterns" section...

## _Famous social media website(s)_

This is actually a dark pattern but it makes use of intentional breaking of Gestalt laws, so it is relevant here. I think the way advertisements show up on social media, be it in scrollable feeds or stories, makes use of the **Gestalt law of continuity**: they present themselves in the _same exact way_ as other posts do, but the latter are meant to be interesting to us (the ads do also rely on "interest" from users but they remain... ads). These promotional posts have a small label -- probably mandatory -- which states they are "Promoted Posts" or "Sponsored", but the UX is such that we usually end up taking about a second looking at them/reading their contents, _before realizing they're ads_. 
This means, as we scroll through posts or tap through stories, we will inevitably be exposed to a significant amount of "unskippable" advertising material. Apart from platforms like Youtube, most social media apps will let you freely scroll past or skip ads, but **integrate them to the feed in such a way that we will still read and remember part of their content**, if they are well made. 


# Dark Patterns & Deceptive Design

## _Another social media website_

One of the most famous social media companies recently (in 2023) added a "consent wall", which forces one to choose between having to pay for a subscription to the website in order to not be tracked for advertisement/not seeing any, or using it for free and one's data being harvested without restriction for advertisement purposes.

The options were:

```"Subscribe to use without ads"``` 
and 
```"Use for free with ads"```

According to [Johnny Ryan on X](https://x.com/johnnyryan/status/1722861499104846034) (formerly Twitter), this is a deceptive choice which "undermines the European Court of Justice's ruling" of July 2023.

## _A classic: the free trial_

To end this article with, here's a common deceptive design pattern that we have all seen at least once: the "free trial" for which you still have to put in your card details. Many, many companies have this option in which the _burden is on the user to remember to cancel_. (via [Mike Calcagno on X](https://x.com/MikeCalcagno/status/1676525562930806788))
It is a dark design pattern in the sense that it was reasonable until recently to assume a free trial would not *punish you* for forgetting to cancel after a month.