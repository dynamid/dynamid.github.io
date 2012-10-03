---
layout: post
title: "JooFlux Initial Public Release"
date: 2012-10-03 12:00
comments: true
categories: jvm java jooflux software release publication invokedynamic
---

The DynaMid members are pleased to announce the initial public release of JooFlux:

> JooFlux a JVM agent that allows both the dynamic replacement of method implementations and the
> application of aspect advices. Compared to existing approaches, JooFlux takes a novel route by
> taking advantage of the new `invokedynamic` instruction added in Java SE 7. The runtime overhead of
> JooFlux is marginal for method invocations, and fairly limited when aspects are being injected. In
> any case, JooFlux shows interesting performance compared to related approaches such as AOP tools or
> dynamic languages that rely on dynamic dispatch. More interestingly, JooFlux does not involve
> reloading whole classes on either method replacement or advice injection, which keeps a large range
> of just-in-time compilation optimizations valid.

JooFlux r0 can be obtained from [https://github.com/dynamid/jooflux](https://github.com/dynamid/jooflux)
and is made available under the terms of the
[Mozilla Public License Version 2.0](http://www.mozilla.org/MPL/2.0/).

While further scientific publications are foreseen, we also released a research technical report called
[**"JooFlux: Hijacking Java 7 InvokeDynamic To Support Live Code Modifications"**](http://hal.inria.fr/hal-00737897).
It is available [on the HAL INRIA open archive](http://hal.inria.fr/hal-00737897), and hopefully soon
on [arXiv](http://arxiv.org/).

We encourage the wider researchers and practitioners community to report any issue with JooFlux, and
contribute bug fixes and improvements.

