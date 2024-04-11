---
permalink: /software/
title: "Software"
header:
  og_image: "software/spatial_weighting.png"
---

## MYCIS: A Clinical Information System Built Exclusively for Taiwan's National Health Insurance (NHI) <a href="https://github.com/chang-ye-tu/mycis"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>

<p align="center">
  <img src="https://chang-ye-tu.github.io/files/img/mycis/main.jpg" width="800"/>
</p>

Taiwan's [NHI](https://en.wikipedia.org/wiki/Healthcare_in_Taiwan#National_Health_Insurance) has officially adopted IC cards in 2004, and this was seen as an important milestone towards healthcare digitalization. However, most of the commercial NHI clinic information systems in the market responded with minimal modifications of their dBase applications; as a result, the data accuracy, performance, and cost-effectiveness are much less than ideal. In view of this, I am determined to develop a reliable, modern and highly automated system. The first version of MYCIS was coded in VB6 and launched in 2005, and it was rewritten in Python in 2011. Based on the positive feedbacks it was refactored and extended in 2016 and [open-sourced](https://github.com/chang-ye-tu/mycis) in 2021.

<p align="center">
  <img src="https://chang-ye-tu.github.io/files/img/mycis/stat.jpg" width="800"/>
</p>

## Ānanda: A Collection of Computer-Assisted Learning / Memorizing Subroutines <a href="https://github.com/chang-ye-tu/ananda"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>

<p align="center">
 <img src="https://chang-ye-tu.github.io/files/img/ananda/thm1.jpg" width="800"/>
</p>

As the authors stated in their [PNAS paper](https://www.pnas.org/content/116/10/3988#:~:text=Spaced%20repetition%20is%20a%20technique,a%20few%20hard%2Dcoded%20parameters.),  
> Spaced repetition is a technique for efficient memorization which uses repeated review of content following a schedule determined by a spaced repetition algorithm to improve long-term retention. However, current spaced repetition algorithms are simple rule-based heuristics with a few hard-coded parameters. ...

Back in 2005 I was learning German but struggled to master the language. Through trial and error I discovered that the [flashcard](https://en.wikipedia.org/wiki/Flashcard) technique powered with [spaced-repetition](https://en.wikipedia.org/wiki/Spaced_repetition) is so effective that I started to write my own flashcard program in VB6. Traditionally the flashcard technique was used exclusively for language acquisition, but left me thinking whether the technique could still be effective in learning / memorizing higher mathematics. One of the greatest obstacles was to properly display mathematics; I found [jsMath](http://www.math.union.edu/~dpvc/jsMath/) and it did the job. This was long before the advent of [Anki](https://apps.ankiweb.net/), the most feature-complete flashcard software, and the rest is history.
 
At the heart of this suite is the integrated pdf & djvu reader and theorem 'harvester' (see figure above); manual flashcard composing and editing can be kept to a minimum and this will greatly facilitate [incremental reading](https://en.wikipedia.org/wiki/Incremental_reading). Surely, one can then edit the flashcard (see figure below) and add supplementary notes with built-in LaTeX support (via [MathJax](https://www.mathjax.org/)).

<p align="center">
 <img src="https://chang-ye-tu.github.io/files/img/ananda/ed1.jpg" width="800"/>
</p>
