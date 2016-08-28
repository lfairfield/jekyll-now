---
layout: post
title: Google Analytics referral spam and co.
---

Not being a big user of analytics, i'll try to refine my best practice when setting up GA.

I, like many, used to just copy and paste google's snippet and consider the job done... then I met weird tracking results.

Advices
I will put the list of "best practices" I come accross and see if and how I apply them.

## use second (or later) properties
Meaning tracking code ending in **-2** or more instead of **-1**.
I can see that working out, but I have been raised with distrust of security by obscurity.
For the fun of it, i may add a second tracking code to this site and see the difference.

## valid hostname filter
From what I gather, this would be whitelisting the target hostnames of the hits. Since I dont reuse tracking code, it should be a short list :P

![Hostname Filter Howto](http://help.analyticsedge.com/wp-content/uploads/valid-hostname-identification.png)

## References:

* [analyticsedge](http://help.analyticsedge.com/spam-filter/definitive-guide-to-removing-google-analytics-spam/)
