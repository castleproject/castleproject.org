---
layout: page
title: DynamicProxy
permalink: /projects/dynamicproxy/

logo_img: castle-logo.png
github: Core
nuget: Castle.Core
---
Castle DynamicProxy is a library for generating lightweight .NET proxies on the fly at runtime. Proxy objects allow calls to members of an object to be intercepted without modifying the code of the class. Both classes and interfaces can be proxied, however only virtual members can be intercepted.

DynamicProxy differs from the proxy implementation built into the CLR which requires the proxied class to extend `MarshalByRefObject`. Extending `MashalByRefObject` to proxy an object can be too intrusive because it does not allow the class to extend another class and it does not allow transparent proxying of classes.

You can use DynamicProxy to generate lightweight proxies on the fly for one or more interfaces or even concrete classes (but only virtual methods will be intercepted).

**Why use proxies?**

Proxy objects can assist in building a flexible application architecture because it allows functionality to be transparently added to code without modifying it. For example, a class could be proxied to add logging or security checking without making the code aware this functionality has been added.

For example, NHibernate, an object/relational mapper uses DynamicProxy to provide lazy loading of data without the domain model classes being aware of this functionality.

For more, [check out the documentation][docs].

[docs]: https://github.com/castleproject/Core/blob/master/docs/dynamicproxy.md