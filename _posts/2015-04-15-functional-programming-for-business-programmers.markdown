---
layout: post
title:  "More is More: Functional Programming for Business and Profit!"
date:   2015-04-15 17:00:00
categories: programming
---

*Functional programming offers many benefits but many line-of-business application developers do not yet
have the tools they need to take full advantage of this.* 

>Many languages have redundant features; progress in language design includes removing those features.<br>
> *--Mark Seemann*

[Functional Programming](http://en.wikipedia.org/wiki/Functional_programming) is becoming more widely used in general purpose computing.
For many of us this change involves the same kinds of mental gymnastics as when we moved from procedural to
object oriented programming (poly-what-ism?), and from relational to document data models (but I almost reached
[fifth normal](http://en.wikipedia.org/wiki/Fifth_normal_form) nirvana!).

<img  src="/images/functional-spaghetti.png"  border="1" alt="Functional Spaghetti">


In his post [*Less is more: language features*](http://blog.ploeh.dk/2015/04/13/less-is-more-language-features/) Mark Seemann adeplty took aim at many sacred cows
from Numbers to Inheritance to NULLs to Exceptions and even Interfaces.

But rather than advocating for any currently existing language Mark seems to be hinting that a better language might be possible
 (though he mentions OCaml, Haskell and F# in passing).

So if we follow Mark's advice to its logical conclusion do we end up with the [Turing Complete](http://en.wikipedia.org/wiki/Turing_complete) equivalent of the following
possible operations?

* `Increment Program Counter`
* `Decrement Program Counter`
* `Update State Register`

Of course not!
                        
But [it has been noted](http://www.infoworld.com/article/2615766/application-development/functional-programming--a-step-backward.html) that
while functional style programming languages may be great for mathematicians they do seem to resemble their [lambda calculus](http://en.wikipedia.org/wiki/Lambda_calculus)
roots a little too closely for your average business programmer.

What's needed for business programmers is the modern **COBOL** or **Visual Basic** but which embodies the most critical
aspects of functional programming in a form that **favors readability over terseness**.
The popularity of those languages in their day should provide clues for those among us choosing programming languages
for productive business application development.

So does that mean in this business programming language operators will look more like this?

* `AND` Instead of `&&&`
* `OR` Instead of `|`
* `AS` Instead of `:?>`
* `LEFT SHIFT` Instead of `<<<`
* `SELECT ... FROM ... WHERE...GROUP BY` instead of `Map/Filter/Reduce` etc...
* along with more familiar ways to express functional composition etc...


Or perhaps we can take this even further if we consider a [Domain Specific Language](http://martinfowler.com/books/dsl.html) where *the domain  is business programming*.
Something like [Gherkin](https://github.com/cucumber/cucumber/wiki/Gherkin) may a be a good example to start with.
A programming language that makes it possible to write [business readable code](http://www.martinfowler.com/bliki/BusinessReadableDSL.html)
may also reduce the need for creating costly external DSLs.

As [noted](http://www.journeytomastery.net/2015/03/27/is-clean-code-less-code/) recently by a software craftsman:

>Is Clean Code less Code? ... I really don't think so.<br>
> *--Nina Hartmann*


*Sometimes more really is more!*
