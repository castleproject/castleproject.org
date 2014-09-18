---
layout: post
title: Castle Core 3.2.1 Bugfix Release
date: 2013-10-05 00:00:00
author: kkozmic
categories: news core
---
It's this time of the year again. Since releasing version 3.2 a few bugs have been fixed; just enough to warrant a point point one release.

There are no breaking changes, and it is an in-place update (the assembly version is still 3.2.0.0, so no assembly redirects are required).

Even though Castle.Core (that is DynamicProxy, DictionaryAdapter and the few other bits it contains) is far from being the hottest open source project in .NET-land, we're still proud to have a great community of users who contribute back.

Seven out of eight fixes in this release came through pull requests from users, so to give credit where credit is due, thanks go to (in no particular order):

* Artur Dorochowicz (@ArturDorochowicz)
* Blair Conrad (@blairconrad)
* Iain Ballard (@i-e-b)
* Jean-Claude Viau (@jcviau)
* Pier Janssen (@Pjanssen)
* Dmitry Xlestkov (@d-s-x)

The full list of changes is, as always, available through [changes.txt][changes-txt], and you can get the updated package from [NuGet][nuget-core].

Happy coding.

[changes-txt]: https://github.com/castleproject/Core/blob/3.2.1/Changes.txt
[nuget-core]: https://www.nuget.org/packages/Castle.Core/