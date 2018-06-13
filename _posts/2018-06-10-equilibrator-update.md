---
layout: post
title:  "eQuilibrator update"
date:   2018-06-10 11:30:00 -0800
categories: biochemistry thermodynamics equilibrator
tags: biochemistry thermodynamics equilibrator
excerpt: Elad just pushed some nice updates to our biochemical thermodynamics calculator eQuilibrator...
---

![eQuilibrator Logo](/assets/equilibrator_logo_large.svg){: .center-image }

[Elad](http://www.imsb.ethz.ch/research/sauer/people/eladnoor.html) just pushed some nice updates to our biochemical thermodynamics calculator [eQuilibrator](http://equilibrator.weizmann.ac.il/). This is as good an opportunity as any to describe some of the nice improvements we've made to eQuilibrator over the last couple years. 

Here's a short list. Over the next couple weeks I'll also be posting short primers on clever ways to use eQuilibrator for teaching and research. 

* Source code is now hosted on [GitLab](https://gitlab.com/elad.noor/equilibrator).
* Elad revamped the UI and logo. 
* Search & suggestions are much faster via [Solr](http://lucene.apache.org/solr/).
* We have a dedicated page for redox [half-reactions](http://equilibrator.weizmann.ac.il/static/classic_rxns/faq.html#what-are-half-reactions) - e.g. [this one](http://equilibrator.weizmann.ac.il/search?query=oxaloacetate+%3D+L-malate).
* [Uncertainty estimates](http://equilibrator.weizmann.ac.il/static/classic_rxns/faq.html#how-do-you-calculate-the-uncertainty-for-each-estimation) for every Gibbs energy.
* Two useful [pathway analysis](http://equilibrator.weizmann.ac.il/pathway/) tools.
* Improved FAQ contents moved to Sphinx.
* A primer on the thermodynamics of central metabolism "[Classic Reactions](http://equilibrator.weizmann.ac.il/static/classic_rxns/classic_reactions/index.html)."

If you have questions, we have a [Google Group](https://groups.google.com/forum/#!forum/equilibrator-users) that we check regularly. If you find bugs or have feature requests, report them on [GitLab](https://gitlab.com/elad.noor/equilibrator/issues) please!