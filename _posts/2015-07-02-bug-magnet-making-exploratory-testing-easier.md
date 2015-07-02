---
layout: post
title:  "Bug Magnet - Making Exploratory Testing easier"
date:   2015-07-02 23:00:00
---

Exploratory Testing is a pretty common activity in a QA's life. It requires curiosity and a good amount of creativity in order to break and/or find defects in an application. Most of web applications have input fields that expect specific user data such as name, age, email, date of birth, credit card and so on. 

So, how can we make sure these input fields can handle different kinds of data correctly?

As we know, a wide variety of test data could be used to verify how consistent these fields are. Sometimes it can be a bit tricky remembering different input possibilities and we may end up not validating the fields properly. In the past years, I've noticed that several web applications still do not handle well different kinds of data.

[Bug Magnet](https://chrome.google.com/webstore/detail/bug-magnet/efhedldbjahpgjcneebmbolkalbhckfi?hl=en) is a Chrome Extension developed by [Gojko Adzik](http://gojko.net/) that brings some interesting test data to make your life easier when testing input fields. The tool is open source and is available in Github [here](https://github.com/gojko/bugmagnet).

