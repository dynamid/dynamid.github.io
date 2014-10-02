---
layout: page
title: "Software"
comments: false
sharing: false
footer: false
---

We release *some* of our research work as [public open source projects on GitHub](https://github.com/dynamid).

Expect more projects to be listed here in the future!

## Golo: a lightweight dynamic language for the JVM.

> Golo is a simple dynamic, weakly-typed language that favours explicit over implicit. You should become a Golo programmer within hours, not days.
> Built from day 1 with `invokedynamic`, Golo takes advantage of the latest advances of the JVM. It is also a showcase on how to build a language runtime with invokedynamic.

* **GitHub repository:** [https://github.com/golo-lang/golo-lang](https://github.com/golo-lang/golo-lang)
* **License:** [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
* **Current version:** `1.1.0` (September 22th 2014).
* **First public release:** March 27th 2013
* **DynaMid Member:** Julien Ponge
* **Status:** platform / early preview

## JooFlux: a Java agent for dynamic aspect-oriented middlewares

> JooFlux a JVM agent that allows both the dynamic replacement of method implementations and the
> application of aspect advices. Compared to existing approaches, JooFlux takes a novel route by
> taking advantage of the new `invokedynamic` instruction added in Java SE 7. The runtime overhead of
> JooFlux is marginal for method invocations, and fairly limited when aspects are being injected. In
> any case, JooFlux shows interesting performance compared to related approaches such as AOP tools or
> dynamic languages that rely on dynamic dispatch. More interestingly, JooFlux does not involve
> reloading whole classes on either method replacement or advice injection, which keeps a large range
> of just-in-time compilation optimizations valid.

* **GitHub repository:** [https://github.com/dynamid/jooflux](https://github.com/dynamid/jooflux)
* **License:** [Mozilla Public License Version 2.0](http://www.mozilla.org/MPL/2.0/)
* **Current version:** `r1` (February 19th 2013).
* **First public release:** October 2012
* **DynaMid Members:** Julien Ponge and Frédéric Le Mouël
* **Status:** research prototype / proof-of-concept

## OSGi substitution library

> OSGi-substitution is an API and OSGi service set to allow service substitution without any restart
> of the client and without any assumption on external services.

* **BitBucket repository:** [https://bitbucket.org/jponge/osgi-substitution](https://bitbucket.org/jponge/osgi-substitution)
* **License:** [LGPLv3](http://www.gnu.org/licenses/)
* **DynaMid Members:** Yufang Dan, Nicolas Stouls, Julien Ponge
* **Status:** proof-of-concept

