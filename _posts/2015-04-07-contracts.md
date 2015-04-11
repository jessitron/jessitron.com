---
layout: talk
title: Contracts and Clojure: the Best-Yet Compromise Between Types and
Tests
deliveries: [
  { date: 2015-04-07, place: "Philly ETE", link: "phillyemergingtech.com" },
  { date: 2015-04-24, place: "Craft Conf", link: "craft-conf.com/2015" },
  { date: 2015-07-04, place: "PolyConf, Poznań, Poland", link: "polyconf.com" }
]
image: coconut.jpg
slides: http://www.slideshare.net/jessitron/contracts-inclojurepete
code: https://github.com/jessitron/contracts-as-types-examples
---
Clojure makes highly functional programming fun… until it isn’t. Runtime
type errors from a function that was returned from another function? I’m
longing for Scala’s compiler errors! Nested maps of data make testing
easier… until “Wait, what’s in there again?” What I want is a little bit
of typing in strategic places: enter Prismatic’s Schema library. What
look like types are really contracts. They’re even more powerful than
types: they verify values as well as shapes. Exercised in generative
tests, these contracts satisfy my type cravings without the pain of
satisfying a compiler. There are limitations; schemas can’t express
relationships between input and output types… or can they? Schemas don’t
express parameterized types… or can they? Explore the potential of
contracts as the best-yet compromise between types and tests. No Clojure
experience needed.
