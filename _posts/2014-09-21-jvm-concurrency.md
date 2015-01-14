---
layout: talk
title: Concurrency Options on the JVM
deliveries: [ { date: 2014-08-21, place: "StrangeLoop", link:
"thestrangeloop.com"} 
]
image: cars.png
slides: https://prezi.com/fr8lerqzxewz/concurrency-options-on-the-jvm/ 
video: https://www.youtube.com/watch?v=yhguOt863nw
---
Nobody uses threads and locks directly anymore, thank goodness.
Instead, we have a plethora of abstractions. Akka
actors, Clojure core.async, Java 8 streams -- they're all beautiful in
their different ways. And none of them free us from thinking about
threads. This talk focuses on the commonalities between high-level
concurrency abstractions, and what you didn't want to have to know, but
should, about the JVM mechanics underneath them.
