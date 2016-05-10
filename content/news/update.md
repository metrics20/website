+++
title = "Updates"
tags = [ "meta"]
date = "2016-05-09"
+++

Hi everybody.
I just made a bunch of changes to the [metrics 2.0 specification](https://github.com/metrics20/spec/blob/master/spec.md) and this [this website](http://www.metrics20.org).

In no particular order:

* clarify what the spec is primarily about (terminology and metric metadata modeling).  Concrete protocol/storage/tsdb/library implementations are secondary. They can be discussed and maintained through this website, and may result in another specification themselves, but they didn't belong in the data model specification.
* untangle metrics 2.0 from the graphite ecosystem where it was born out of.  Graphite - and its metrics2.0 tooling - is still important, but there's a lot of other systems we want to work with
* new markdown format for easier editing
* the model of a metric identified as nothing but a set of tags is too weird for many.  The update acknowledges an extra 'key' that is often used in many systems.

