---
layout: post
title: Castle Core 3.3.3 Bugfix Release
date: 2014-11-06 00:00:00
author: jonorossi
categories: news core
---
The last release of Castle Core had two more defects in the new Serilog integration:
* [#69][github-core-69] was an omission where the Castle's logger name wasn't passed to Serilog.
* [#70][github-core-70] was a defect that calling `Create(string name, LoggerLevel level)` had a side-effect of modifying the passed in `LoggerConfiguration`,
  this overload shouldn't have been implemented on this integration as the logger level should be configured via Serilog.

We just pushed an update that fixes the problems. There are no other changes in this release.

[github-core-69]: https://github.com/castleproject/Core/issues/69
[github-core-70]: https://github.com/castleproject/Core/issues/70