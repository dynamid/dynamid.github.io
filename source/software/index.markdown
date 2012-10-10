---
layout: page
title: "software"
comments: false
sharing: false
footer: false
---

We release *some* of our research work as [public open source projects on GitHub](https://github.com/dynamid).

Expect more projects to be listed here in the future!

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
* **First public release:** October 2012
* **Members:** Julien Ponge and Frédéric Le Mouël
* **Status:** research prototype / proof-of-concept
* **Current version:** `r0`

