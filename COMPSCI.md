# Computer science

(This section leans toward relatively language-agnostic resources.)

## Distributed systems

- [_Designing Data-Intensive Applications_ (DDIA)](https://dataintensive.net/), Kleppmann, 2017. Fantastic tome full of sick burns, helpful industry case studies, and conceptual frameworks for robustly tailoring data-intensive distributed systems architecture to different scenarios. Accessible but dense; the ideal target reader has past experience in large-scale data engineering or distsys to tie the concepts back to. Without past experience, this may come off as an overwhelming potpourri of endless acronyms/references and just taking Kleppmann's word for whatever he's saying.

## Systems

- I liked [jmeiners' tutorial] on writing your first toy virtual machine. Did a [C implementation here](https://github.com/rfong/lc3-vm-c).

### Conflict-free replicated data types (CRDTs)

A data structure that simplifies distributed data storage by guaranteeing eventual consistency. Commonly used for distributed RTC (real-time collaborative) software, multi-device syncing, and robust distributed database replication.

- [CRDT.tech](https://crdt.tech/): Summary and collection of resources for learning about CRDTs.
- [CRDTs: The Hard Parts](https://www.youtube.com/watch?v=x7drE24geUw) is a 70m talk by Kleppmann on how it's easy to satisfy the technical definition of a CRDT, but some reasons it's hard to build ones that satisfy intuitive end-user expectations.

## Computer graphics

- [MIT 6.837 Computer Graphics](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-837-computer-graphics-fall-2012/)

### Shaders

Graphics programs optimized to leverage a GPU's rendering pipeline for real-time performance.

- [The Book of Shaders](https://thebookofshaders.com/): an interactive, explorable, online introduction to writing (and more importantly, _thinking in_) shaders. Very mind-bending.
- [Shadertoy](https://www.shadertoy.com/): online interactive-coding platform for sharing & previewing shaders. Fantastic place to get inspired and see how different effects are achieved.

## NLP (Natural Language Processing)

The field of computationally making inferences about _natural language_, that is, language generated by humans for humans. I personally only deal in traditional statistical & Bayesian NLP.

- [Natural Language Processing with Python](https://www.nltk.org/book/): written by the authors of the popular `nltk` Python module for doing NLP. Very hands-on walkthrough to common statistical NLP operations through `nltk` features.
- [MIT 6.864](https://www.mit.edu/~jda/teaching/6.864/sp20/) (Advanced Natural Language Processing). I originally took it in 2011, when it was a purely statistical and supervised-learning based field in the era before RNNs gained widespread utility, so it's expanded a bit recently.

## Algorithms

- _Introduction to Algorithms, 3rd ed._ (1989), better known as [CLRS](https://mitpress.mit.edu/books/introduction-algorithms-third-edition) after the initials of its authors. Canonical classic CS textbook.
- USACO (USA Computing Olympiad) [training resources](http://www.usaco.org/index.php?page=training). I grew up on these and my interest in computer science probably began here. Great hands-on approach to thinking about clever algorithmic design and performance optimization, through the allegory of cows.

## HCI (Human-Computer Interfaces)

### Data visualization

[NYU's Information Visualization Specialization](https://www.coursera.org/specializations/information-visualization) is a truly excellent series of courses on effective data visualization through knowledge of how human perception works.
- I found the first and fourth courses most useful.
- The hands-on exercises are fantastic for understanding how to evaluate and construct objectively effective visualizations.
- The second course on color theory may be common knowledge if you have a little visual arts background, but is useful if you aren't familiar with optimizing a user interface for partial colorblindness.
- The third course may be skipped entirely if you prefer to get familiar with code libraries via hands-on exercises and docsets (rather than lectures), but may be useful if you are unfamiliar with frontend programming and prefer to learn via audio lectures.
