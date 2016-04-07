---
layout: post
title: Windsor and Core 3.2 is released
date: 2013-02-16 00:00:00
author: kkozmic
categories: news windsor core
---
Windsor 3.2 release is now live on [nuget][nuget-windsor] and [sourceforge][sfnet-windsor].

This release also contains updated Core library.

This release is mostly about bugfixes and incremental improvements and while some breaking changes were made, for vast majority of users this will be a drop-in update.

The highlights of the release [are in the documentation][docs-whats-new], so I won't repeat them here.

## End of an era
It is the last release to support .NET 3.5 and Silverlight.

Also, I'm thinking of sunsetting (such a nice word) Remoting Facility, Factory Support facility (the one that allows you to specify factory method via XML, not to be confused with Typed Factory facility), Event Wiring facility and Synchronize facility.

Obviously, Windsor being a community driven project, if someone wants to step in and take over any of these facilities we'll keep updating them. Otherwise this will likely be their last release.

[nuget-windsor]: http://nuget.org/packages/Castle.Windsor
[sfnet-windsor]: https://sourceforge.net/projects/castleproject/files/latest/download
[docs-whats-new]: https://github.com/castleproject/Windsor/blob/master/docs/whats-new-3.2.md