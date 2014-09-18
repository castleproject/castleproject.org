---
layout: post
title: Windsor 3.2.1 Bugfix Release
date: 2013-07-22 00:00:00
author: kkozmic
categories: news windsor
---
We just released a bugfix release for Windsor, version 3.2.1.

It fixes a problem some users encountered, when CallContext scoped lifestyle is used in certain cross-AppDomain contexts. It specifically affected users of some testing framework or NServiceBus when deployed to Azure. The bug would manifest itself with the following exception:

    SerializationException — Type is not resolved for member "Castle.MicroKernel.Lifestyle.Scoped.CallContextLifetimeScope+SerializationReference,Castle.Windsor, Version=3.2.0.0, Culture=neutral, PublicKeyToken=407dd0808d44fbdc"

The package [is available on NuGet][nuget-windsor] now.

[nuget-windsor]: https://www.nuget.org/packages/Castle.Windsor/