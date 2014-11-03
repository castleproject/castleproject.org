---
layout: post
title: Castle Core 3.3.2 Bugfix Release
date: 2014-11-03 00:00:00
author: jonorossi
categories: news core
---
The last release of Castle Core had [an implementation bug][github-core-66] in the new Serilog integration where exceptions for some of the ILogger overloads wouldn't be passed through correctly.

We just pushed an update that fixes the problem. There are no other changes in this release.

[github-core-66]: https://github.com/castleproject/Core/issues/66