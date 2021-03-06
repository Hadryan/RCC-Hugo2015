---
title: HHKB Keyboard Driver Status
subtitle: ... on OS X El Capitan 10.11
slug: pfu-hhkb-keyboard-osx-el-capitan-status
banner: /img/Cogley-Banner-Train-Romance-Car-1170x350-003-mono.jpg
date: 2016-02-02T08:59:00+09:00
publishdate: 2015-10-06T15:20:15+09:00
description: 'Status of PFU Happy Hacking Keyboard HHKB Drivers on OS X El Capitan, a post by Rick Cogley.'
draft: 'false'
images:
  - /img/Cogley-Post-PFU-HHKB-Pro-JP.jpg
  - /img/Cogley-Banner-Train-Romance-Car-1170x350-003-mono.jpg
  - /img/rick-cogley-avatar-240x240.png
tags:
  - osx
  - bug
  - HHKB
  - Keyboard
  - 10.11
  - El Capitan
  - PFU
  - driver
  - SIP
  - Seil
  - Topre
topics:
  - Software
  - Tips
  - Troubleshooting
postsummary: If you jumped on the OS X El Capitan upgrade, and you are a user of the PFU HHKB "Happy Hacking" keyboard with its buttery-smooth yet perfectly-firm Topre switches, you might have noticed it does not work.
postsvg: icon-origami-fish
---

If you jumped on the OS X El Capitan upgrade, and you are a user of the PFU HHKB "Happy Hacking" keyboard with its buttery-smooth yet perfectly-firm [Topre switches](https://deskthority.net/wiki/Topre_switch), you might have noticed it does not work. (**Note**: now fixed, see update section and if you install, you can disable the relevant part of Seil if you were using it.)
<!--more-->

## HHKB OS X El Capitan Status

I noticed that my PFU HHKB's don't work, after upgrading to OS X El Capitan. I use the Type-S ones with the Japanese layout, and I imagine that due to the new "SIP" System Integrity Protection that Apple has implemented, the old drivers from 2012 are kaput. This is what Apple has to say about that new system:

> **System Integrity Protection** - A new security policy that applies to every running process, including privileged code and code that runs out of the sandbox. The policy extends additional protections to components on disk and at run-time, only allowing system binaries to be modified by the system installer and software updates. Code injection and runtime attachments to system binaries are no longer permitted.

{{< figure1 link="/img/Cogley-Post-PFU-HHKB-Pro-JP.jpg" src="/img/Cogley-Post-PFU-HHKB-Pro-JP.jpg" type="Photo" title="Rick's PFU HHKB Pro JP keyboard" >}}

I speak Japanese so I contacted PFU, only to get some corporate double-speak in reply. After some back-and-forth in which I whined and brayed about the fact that I have to reach my paws all the way up to use my actual laptop keyboard (first world problem, huh?), PFU told me that they are "actively developing it, and expect to complete it soon." I hope that is true.

The tech pointed me at their [Japanese FAQ page](http://www.pfu.fujitsu.com/hhkeyboard/hhkb_support/faq_el_capitan.html), on which he says's they'll publish new info, once they are ready.

So stay tuned, folks.

## Updates

### 3 Dec 2015

PFU sent an email saying that they had released the driver, now available [here](http://www.pfu.fujitsu.com/hhkeyboard/download.html). Specifically:

* [HHKB Pro, Pro2, Pro HG, Pro JP, Type-S Mac Driver](http://www.pfu.fujitsu.com/hhkeyboard/macdownload.html)
* [HHKB Lite2 Driver](http://www.pfu.fujitsu.com/hhkeyboard/macdownload_lite2.html)

If you're using Seil as a workaround, be sure to un-check the checkboxes in the Japanese section, that you enabled.

### 20 Nov 2015

PFU states on their FAQ site that they should be able to release updated drivers for OS X El Capitan near the end of Nov 2015.

### 30 Oct 2015

{{< figure1 link="/img/Cogley-Post-PFU-HHKB-fixed-on-El-Capitan-by-Seil-20151030.png" src="/img/Cogley-Post-PFU-HHKB-fixed-on-El-Capitan-by-Seil-20151030.png" type="Screenshot" title="Use Seil to Fix PFU HHKP Pro JP Type-S keyboard on El Capitan" >}}


I've followed up with PFU several times since this post, and although they now say they have a beta available, they won't let me test it. Whatever. I confirm you can fix it using [Seil](https://pqrs.org/osx/karabiner/seil.html.en), though. Just download Seil, mount its ``.dmg``, double click the installer and follow the prompts. Then just run it, and set the three checkboxes you can see in the screenshot. _Click to embiggen <<_.
