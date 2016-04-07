---
layout: post
title: Windsor and Core 3.1 released
date: 2012-08-05 00:00:00
author: kkozmic
categories: news windsor core
---
Windsor and Core (and the usual facilities) version 3.1 have been released today. There are no changed since [the RC][blog-rc-post] except for reverting one breaking change.

This is probably the last version to support Silverlight.

We have a [what's new page in the wiki][docs-whats-new], and as always, the package contains a detailed changelog and list of breaking changes.

## Downloads
* [Windsor (and facilities)][sfnet-windsor]
* [Core (and logging adapters for NLog and log4net 1.2.10)][sfnet-core]

## NuGet
    # Windsor:
    Install-Package Castle.Windsor
    
    # WCF Facility:
    Install-Package Castle.WcfIntegrationFacility
    
    # Synchronize Facility:
    Install-Package Castle.SynchronizeFacility
    
    # Remoting Facility:
    Install-Package Castle.RemotingFacility
    
    # Event Wiring Facility:
    Install-Package Castle.EventWiringFacility
    
    # Factory Support Facility:
    Install-Package Castle.FactorySupportFacility
    
    # Logging Facility:
    Install-Package Castle.LoggingFacility
    
    # Logging Facility log4net:
    Install-Package Castle.Windsor-log4net
    
    # Logging Facility NLog:
    Install-Package Castle.Windsor-nlog
    
    # Core:
    Install-Package Castle.Core
    
    # Logging adapter for log4net:
    Install-Package Castle.Core-log4net
    
    # Logging adapter for NLog:
    Install-Package Castle.Core-NLog

[blog-rc-post]: {% post_url 2012-07-07-windsor-3-1-rc-released %}
[docs-whats-new]: https://github.com/castleproject/Windsor/blob/master/docs/whats-new-3.1.md
[sfnet-windsor]: http://sourceforge.net/projects/castleproject/files/Windsor/Castle.Windsor.3.1.0.zip/download
[sfnet-core]: http://sourceforge.net/projects/castleproject/files/Core/Castle.Core.3.1.0.zip/download