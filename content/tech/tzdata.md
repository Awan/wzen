---
layout: post
author: Abdullah
title:  Set time zone in Debian, Ubuntu, Raspberry Pi(Raspbian)
date: 2019-09-11
slug: tzdata
description: How to set timezone in Debian based distributions
tags:
  - tzdata
  - timezone
  - date
---

Sometimes we install systems and don't care about setting timezone. Or we travel to some other countries where timezone is different. So here is how you can change timezone in Debian, Ubuntu, Mint, Raspbian and almost all distributions derived from Debian.

```
# dpkg-reconfigure tzdata
```
You will see a dialog box opened.

{{< figure src=/images/tzdata-continent.png title="Select continent" >}}

Select your continent.

Hit enter after selecting your continent using arrow keys.

{{< figure src=/images/tzdata-city.png title="Select city" >}}

Select your city and hit Enter. Voila, you are done! 
