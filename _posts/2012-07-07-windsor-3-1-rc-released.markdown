---
layout: post
title: Windsor 3.1 (RC) released
date: 2012-07-07 00:00:00
author: kkozmic
categories: news windsor
---
It's that time of year again. Windsor 3.1 is a minor update and while it contains few breaking changes for most people it should be a update, recompile, run experience.

We have a [what's new page in the wiki][docs-whats-new], and as always, the package contains a detailed changelog and list of breaking changes.

The release is considered stable and is being used in production, but please install it, try it out, and if you notice any issues let us know. If everything is fine expect final 3.1 release by the end of the month.

## Downloads
* [Windsor (and facilities)][sfnet-windsor]
* [Core (and logging adapters for NLog and log4net 1.2.10)][sfnet-core]

## NuGet
    # Windsor:
    Install-Package Castle.Windsor -Pre
    
    # WCF Facility:
    Install-Package Castle.WcfIntegrationFacility -Pre
    
    # Synchronize Facility:
    Install-Package Castle.SynchronizeFacility -Pre
    
    # Remoting Facility:
    Install-Package Castle.RemotingFacility -Pre
    
    # Event Wiring Facility:
    Install-Package Castle.EventWiringFacility -Pre
    
    # Factory Support Facility:
    Install-Package Castle.FactorySupportFacility -Pre
    
    # Logging Facility:
    Install-Package Castle.LoggingFacility -Pre
    
    # Logging Facility log4net:
    Install-Package Castle.Windsor-log4net -Pre
    
    # Logging Facility NLog:
    Install-Package Castle.Windsor-nlog -Pre
    
    # Core:
    Install-Package Castle.Core -Pre
    
    # Logging adapter for log4net:
    Install-Package Castle.Core-log4net -Pre
    
    # Logging adapter for NLog:
    Install-Package Castle.Core-NLog -Pre

[docs-whats-new]: http://docs.castleproject.org/Windsor.Whats-New-In-Windsor-31.ashx
[sfnet-windsor]: http://sourceforge.net/projects/castleproject/files/Windsor/Castle.Windsor.3.1-RC.zip/download
[sfnet-core]: http://sourceforge.net/projects/castleproject/files/Core/Castle.Core.3.1-RC.zip/download