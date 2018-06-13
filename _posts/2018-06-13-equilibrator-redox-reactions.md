---
layout: post
title:  "eQuilibrator: Redox Reactions"
date:   2018-06-13 08:00:00 -0800
categories: biochemistry thermodynamics equilibrator
tags: biochemistry thermodynamics equilibrator redox
excerpt: An electron carrier is a molecule that can stably occupy reduced and oxidized states - like NAD+ and NADH diagrammed below. Most biological redox reactions involve the enzyme-catalyzed transfer of electrons to or from an electron carrier...
---

![eQuilibrator Logo](/assets/equilibrator_logo_large.svg){: .center-image }

An electron carrier is a molecule that can stably occupy reduced and oxidized states - like NAD+ and NADH diagrammed below. Most biological redox reactions involve the enzyme-catalyzed transfer of electrons to or from an electron carrier. If you took a biochemistry class at some point you probably learned about the common biological e- carriers: [NAD(P)H](https://en.wikipedia.org/wiki/NAD%2B), [FADH<sub>2</sub>](https://en.wikipedia.org/wiki/Flavin_adenine_dinucleotide), various [quinones](https://en.wikipedia.org/wiki/Quinone#Biochemistry), [ferredoxins](https://en.wikipedia.org/wiki/Ferredoxin) and, if you were lucky, the archaeal carrier [coenzyme F420](https://en.wikipedia.org/wiki/Coenzyme_F420). 

![Oxidized NAD+](/assets/NADox.gif){: .center-image }
![Reduced NADH](/assets/NADred.gif){: .center-image }

Electron carriers are characterized quantitatively by their reduction potentials (usually in mV units). A carrier with a +100 mV potential will more readily accept electrons than one with -100 mV potential because electrons flow to positive potential by convention. If you know the potential of the electron donor and acceptor in a redox reaction, you can  calculate the Δ<sub>r</sub>G of that reaction (read more [here](http://book.bionumbers.org/what-is-the-redox-potential-of-a-cell/) and [here](http://equilibrator.weizmann.ac.il/static/classic_rxns/classic_reactions/glycolysis.html#nadh-as-an-electron-carrier)). 

Many biological electron carriers are straightforward to think about in that they are small, defined molecules that we can purify and characterize in the lab. NAD(P)H and FADH<sub>2</sub> are great examples - it is relatively easy to measure the redox potential of these carriers because it is clear what they are. But this is not the case for all e- carriers. Ferredoxins, for example are proteins containing an iron-sulfur cluster and their redox potentials can vary by more than 200 mV depending on the exact sequence of the protein. As such, we can't reasonably attach a number to ferredoxin in eQuilibrator - unless you have a list of potentials for all the ferredoxin genes in nature you want to share. 

[Iron is a problem in general](http://equilibrator.weizmann.ac.il/static/classic_rxns/faq.html#what-s-so-complicated-about-redox-reactions-involving-iron), really. Some bacteria draw electrons (and, thereby energy for growth) from iron-containing minerals. But these minerals can differ in composition and, therefore, redox potential pretty substantially. On top of that *I am not a minerologist.* So [Elad](http://www.imsb.ethz.ch/research/sauer/people/eladnoor.html) came up with an elegant solution to dealing with redox reactions involving problematic donors or acceptors in eQuilibrator - you just tell us what the potential is. 

You can try it by example using the oxidation of glucose to gluconate - "[glucose + H<sub>2</sub>O = gluconate](http://equilibrator.weizmann.ac.il/search?query=Glucose+%2B+H2O+%3D+Gluconate)". If the electrons will be donated to the Spirulina ferredoxin II, which has a [-305 mV potential](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1183753/) you can simply enter -305 into the text box labeled "e- potential" and click "Update" to calculate the Δ<sub>r</sub>G' value you came for. 

