---
layout: post
title: Castle Core 3.2.2 Bugfix Release
date: 2013-11-30 00:00:00
author: kkozmic
categories: news core
---
Last release of Castle Core had the unfortunate side-effect that one of the fixes included was susceptible to hitting [a bug in the BCL][msconnect-716160].

We just pushed an update that works around the problem. See the [bug report][github-core-35] and related [pull request][github-core-36] for details.

There are no other changes in this release.

The fix was contributed by [@jonasro](https://github.com/jonasro)

[msconnect-716160]: http://connect.microsoft.com/VisualStudio/feedback/details/716160/cannot-use-parameterbuilder-setconstant-with-an-empty-nullable
[github-core-35]: https://github.com/castleproject/Core/issues/35
[github-core-36]: https://github.com/castleproject/Core/pull/36