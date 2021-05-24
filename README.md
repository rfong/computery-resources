Some favorite computery resources relevant to my interests.

### Context: learning modalities

My preferred learning modalities are text-based, visual, and exploratory, and I tend to not do so well with audio. Any recommendations I make may not necessarily work well for people who prefer audio to text, or who have difficulty with spatial intuition.

There are not a lot of straightforward how-to resources in this list; it's more skewed toward foundational understanding & conceptual frameworks.

-----
# Computer science & related concepts

## Distributed systems

- [_Designing Data-Intensive Applications_ (DDIA)](https://dataintensive.net/), Kleppmann, 2017. Fantastic tome full of sick burns, helpful industry case studies, and conceptual frameworks for robustly tailoring data-intensive distributed systems architecture to different scenarios. Accessible but dense; the ideal target reader has past experience in large-scale data engineering or distsys to tie the concepts back to.

### Conflict-free replicated data types (CRDTs)

A data structure that simplifies distributed data storage by guaranteeing eventual consistency. Commonly used for distributed RTC (real-time collaborative) software, multi-device syncing, and robust distributed database replication.

- [CRDT.tech](https://crdt.tech/): Summary and collection of resources for learning about CRDTs.
- [CRDTs: The Hard Parts](https://www.youtube.com/watch?v=x7drE24geUw) is a 70m talk by Kleppmann on how it's easy to satisfy the technical definition of a CRDT, but some reasons it's hard to build ones that satisfy intuitive end-user expectations.

## Computer graphics

### Shaders

Graphics programs optimized for the GPU's rendering pipeline for high real-time performance.

- [The Book of Shaders](https://thebookofshaders.com/): an interactive, explorable, online introduction to writing (and more importantly, _thinking in_) shaders. Very mind-bending.
- [Shadertoy](https://www.shadertoy.com/): online interactive-coding platform for sharing & previewing shaders. Fantastic place to get inspired and see how different effects are achieved.

## NLP (Natural Language Processing)

The field of computationally making inferences about _natural language_, that is, language generated by humans for humans.

- [Natural Language Processing with Python](https://www.nltk.org/book/): written by the authors of the popular `nltk` Python module for doing NLP. Very hands-on walkthrough to common statistical NLP operations through `nltk` features.
- [MIT 6.864](https://www.mit.edu/~jda/teaching/6.864/sp20/) (Advanced Natural Language Processing). I originally took it in 2011, when it was a purely statistical and supervised-learning based field in the era before RNNs gained widespread utility, so it's expanded a bit recently.

## Algorithms

- _Introduction to Algorithms, 3rd ed._ (1989), better known as [CLRS](https://mitpress.mit.edu/books/introduction-algorithms-third-edition) after the initials of its authors. Canonical classic CS textbook.
- USACO (USA Computing Olympiad) [training resources](http://www.usaco.org/index.php?page=training). I grew up on these and my interest in computer science probably began here. Great hands-on approach to thinking about clever algorithmic design and performance optimization, through the allegory of cows.


-----
# Software engineering

## Observability (o11y)

Software observability is the ability to answer unknown-unknowns, or to derive understanding about systems too complex for humans to fully understand, through making dynamic inquiries and empirical observations about that system's behavior/state.

As far as I know, this term was pioneered by [Honeycomb.io](https://honeycomb.io), which is also my former employer and my absolute favorite tool for asking complex questions of complex software systems. It achieves this through high-cardinality query performance over extremely large bodies of structured timestamped log data and discoverable persistent queries.

Observability is extremely distinct from _monitoring_, in which complex bodies of data are (lossily) pre-aggregated to answer known-unknowns.

## Systematic debugging

- ["Computers Can Be Understood" (Nelson Elhage)](https://blog.nelhage.com/post/computers-can-be-understood/)


-----
# Language/framework-specific

## Golang (2009)

todo

## Rust (2010)

todo

## Clojure (2007)

Released 2007.

An expressive functional language that runs on the JVM and has built-in concurrency and immutable data structures. Was specifically created to address frustrations with the weaknesses of OOP (object-oriented programming) in dealing with concurrent programming.

- [_The Joy of Clojure_](https://www.manning.com/books/the-joy-of-clojure-second-edition), Michael Fogus & Chris Hauser, 2014. A Socratic exploration of the reasoning behind Clojure's design paradigms and idiomatic usage, and how to think in Clojure.
- [Leiningen](http://leiningen.org/), invoked as `lein`, is a commonly used Clojure project manager that helps you manage dependencies, run tests, package your project, etc.
- [`lein` quickstart by BraveClojure](https://www.braveclojure.com/getting-started/), with bonus explanation of how Clojure utilizes the JVM
- [ClojureScript Koans](http://clojurescriptkoans.com/): interactive website that poses simple expressions to which you write solutions to learn how to think in the Clojure paradigm.

## Python 3

### Environment management

- [pyenv](https://github.com/pyenv/pyenv): for managing multiple Python installations on the same machine.

### Formatting

todo

### `asyncio`

- [8-part video series](https://www.youtube.com/watch?v=Xbl7XjFYsN4&list=PLhNSoGM2ik6SIkVGXWBwerucXjgP1rHmB) on how asyncio works, stepping through the event loop, using coroutines, the inner workings of coroutines. Also includes a prelude on the history and context of its design.

### `twisted`

- https://www.infoq.com/presentations/Twisted-Python/


-----
# Other tooling & platforms

## Real-time collaboration (RTC)

- [coderpad.io](http://coderpad.io/): excellent RTC coding platform with interactive shell and support for ~35 languages. Targeted at interviewers.

## Web hosting

- Honestly, [Github Pages](https://pages.github.com/) is unbeatable for free static website hosting.


-----
# Corpora & datasets

## NLP (Natural Language Processing)

- [Wordnet](https://wordnet.princeton.edu/): a richly-annotated lexical database of the English language. Indispensable for semantic disambiguation between homonymic word senses.
- Unix standard file of English dictionary words: `/usr/share/dict/words` or `/usr/dict/words`. Indispensable for quick hacks.

## Computational geometry

- [Shapenet](https://shapenet.org/): a very large, richly-annotated dataset of 3D shapes. (Word of warning: Last time I used it, there were occasional typos in the metadata which you will need to resolve programmatically or manually.)
