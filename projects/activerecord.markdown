---
layout: page
title: ActiveRecord
permalink: /projects/activerecord/

logo_img: castle-logo.png
github:
sfnet: ActiveRecord
---
The **Castle ActiveRecord** project is an implementation of the [ActiveRecord pattern][wikipedia-ar-pattern] for .NET. The ActiveRecord pattern consists of instance properties representing a record in the database, instance methods acting on that specific record and static methods acting on all records.

**Castle ActiveRecord** is built on top of [NHibernate][nhibernate], but its attribute-based mapping frees the developer of writing XML for database-to-object mapping, which is needed when using NHibernate directly.

[Check out the documentation][docs].

[docs]: http://docs.castleproject.org/Active%20Record.MainPage.ashx
[wikipedia-ar-pattern]: http://en.wikipedia.org/wiki/Active_record
[nhibernate]: http://www.nhibernate.org/