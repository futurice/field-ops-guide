# Field Ops Guide

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Sponsored](https://img.shields.io/badge/chilicorn-sponsored-brightgreen.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAA4AAAAPCAMAAADjyg5GAAABqlBMVEUAAAAzmTM3pEn%2FSTGhVSY4ZD43STdOXk5lSGAyhz41iz8xkz2HUCWFFhTFFRUzZDvbIB00Zzoyfj9zlHY0ZzmMfY0ydT0zjj92l3qjeR3dNSkoZp4ykEAzjT8ylUBlgj0yiT0ymECkwKjWqAyjuqcghpUykD%2BUQCKoQyAHb%2BgylkAyl0EynkEzmkA0mUA3mj86oUg7oUo8n0k%2FS%2Bw%2Fo0xBnE5BpU9Br0ZKo1ZLmFZOjEhesGljuzllqW50tH14aS14qm17mX9%2Bx4GAgUCEx02JySqOvpSXvI%2BYvp2orqmpzeGrQh%2Bsr6yssa2ttK6v0bKxMBy01bm4zLu5yry7yb29x77BzMPCxsLEzMXFxsXGx8fI3PLJ08vKysrKy8rL2s3MzczOH8LR0dHW19bX19fZ2dna2trc3Nzd3d3d3t3f39%2FgtZTg4ODi4uLj4%2BPlGxLl5eXm5ubnRzPn5%2Bfo6Ojp6enqfmzq6urr6%2Bvt7e3t7u3uDwvugwbu7u7v6Obv8fDz8%2FP09PT2igP29vb4%2BPj6y376%2Bu%2F7%2Bfv9%2Ff39%2Fv3%2BkAH%2FAwf%2FtwD%2F9wCyh1KfAAAAKXRSTlMABQ4VGykqLjVCTVNgdXuHj5Kaq62vt77ExNPX2%2Bju8vX6%2Bvr7%2FP7%2B%2FiiUMfUAAADTSURBVAjXBcFRTsIwHAfgX%2FtvOyjdYDUsRkFjTIwkPvjiOTyX9%2FAIJt7BF570BopEdHOOstHS%2BX0s439RGwnfuB5gSFOZAgDqjQOBivtGkCc7j%2B2e8XNzefWSu%2BsZUD1QfoTq0y6mZsUSvIkRoGYnHu6Yc63pDCjiSNE2kYLdCUAWVmK4zsxzO%2BQQFxNs5b479NHXopkbWX9U3PAwWAVSY%2FpZf1udQ7rfUpQ1CzurDPpwo16Ff2cMWjuFHX9qCV0Y0Ok4Jvh63IABUNnktl%2B6sgP%2BARIxSrT%2FMhLlAAAAAElFTkSuQmCC)](http://spiceprogram.org/oss-sponsorship)

*The Field Ops Guide* is a booklet that makes it possible to survive a software development project. It's a distillation of years of wisdom gathered working in client projects.

<img src="https://github.com/futurice/field-ops-guide/raw/master/field-ops-guide-at-hand.jpg" alt="The Futurice Field Ops Guide" title="The Futurice Field Ops Guide!" width="300">

## Downloads

- [PDF](dist/field-ops-guide.pdf) for convenient on-screen reading
- [EPUB](dist/field-ops-guide.epub) and [Mobi](dist/field-ops-guide.mobi), for e-book readers

Kindle users, the Mobi should be your best option.

## Design criteria

- helps save human lives
- fits your pocket: not too thick, not too rigid (~A6 size)
- combines a guide and a notebook in one, making it multi-purpose
- should contain the most important things, and *only* the most important things
- usable by anyone in a client project
- inexpensive enough to be forgotten lying around rather carelessly

Future ideas:

- [ ] double as a field shovel
- [ ] add a fragrance for that little extra touch (a gentle napalm-lavender mix?)

## How did it happen?

In military and aviation, similar checklists are used to avoid total catastrophes. A few folks from Futurice Tampere office got interested about the idea of doing a similar "field ops guide" that might just be enable a person to work in a challenging software project and live to tell stories about it.

We decided on a format that asks a number of questions per project phase. One should be able to answer each question with a "yes", or fail to do so only on purpose and with good reasoning.

The work started as part of the Tammerforce Tech Vision Working Group in late 2017, and the first version finally came out of print in late 2018 (phew!)

### Team

The content was compiled and written by [Miro Nieminen](https://github.com/miro), Antti Partanen, [Sakari Hyöty](https://github.com/shyoty) and [Mike Arvela](https://github.com/mieky), with additional ideas and feedback gathered from colleagues.

Ella Eiranto is the one who made it look and feel superb. In addition to designing the visual style for the Guide, Ella also did all the work getting the booklet printed.

Also thanks for the support to Kalle Aaltonen, Kari-Pekka Koljonen, Jari Suksi, Riku Valtasola & Osmo Haapaniemi, and all the others for their valuable input.

## How to convert to EPUB

To convert Markdown to EPUB, run [pandoc](https://pandoc.org/) with something like this:

`pandoc --toc --toc-depth=3 --epub-cover-image="src/field-ops-guide-cover.jpg" -o dist/field-ops-guide.epub src/field-ops-guide.md`

To further convert EPUB to MOBI, run [kindlegen](https://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211):

`kindlegen dist/field-ops-guide.epub`

## How to order

See [src/print](src/print) for specs used for recent orders, as well as Illustrator-editable PDF source files.

## Contributing

The Field Ops Guide is free and open source. Issues and pull requests are most welcome!

[<img alt="The Chilicorn" src="http://spiceprogram.org/assets/img/chilicorn_sticker.svg" width="250" height="250">](https://spiceprogram.org/oss-sponsorship)

