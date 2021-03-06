---
layout: post
title:  "On Automating Tests"
date:   2014-11-14 11:46:23
categories: testing
---

I recently came across a nice blog post on writing unit tests:

[Writing Great Unit Tests: Best and Worst Practices](http://blog.stevensanderson.com/2009/08/24/writing-great-unit-tests-best-and-worst-practises/)

The challenging premise here is "Unit testing is not about finding bugs".
The author then goes on to explain unit tests _**are**_ good for finding bugs when refactoring.  However when you are initiailly creating unit tests the focus is more on design (TDD).

Perhaps more valuable here is this chart:

![](/images/httpblog.stevensanderson.comwp-contentuploads200908image.png)

So basically try to create unit tests on lower level testable units.  Make integration tests for higher level tests of the integrated system.  Avoid creating hybrid tests in-beteween the two (even though it's not 100%, there is a spectrum).  When refactoring time comes you'll be in good shape.
