---
layout: post
title:  "Revisiting tradeoffs between rubisco kinetic parameters"
date:   2020-10-21 13:30:00 -0800
published: true
categories: publications
tags: co2-fixation rubisco calvin-cycle
excerpt: All plants, algae and cyanobacteria rely on the Calvin-Benson-Bassham (CBB) cycle for growth. Rubisco is the central enzyme of the CBB cycle and the most abundant enzyme on the planet. It does the tricky bit where CO<sub>2</sub> gets "fixed" onto a soluble sugar. While it is often said that rubisco is "slow," it is actually an average enzyme in terms of "turnover number" (maximum rate per active site, k<sub>cat</sub>). The true rate of rubisco carboxylation is much slower than its k<sub>cat</sub>, however, because rubisco can react non-specifically with O<sub>2</sub>. I certainly think it's surprising that rubisco is not faster or more specific given how important and abundant it is. 
---

This post is a reflection on and summary of my recent work with collaborators: Flamholz AI, Prywes N, Moran U, Davidi D, Bar-On YM, Oltrogge LM, Alves R, Savage D, Milo R. 2019. [Revisiting Trade-offs between Rubisco Kinetic Parameters](https://pubs.acs.org/doi/10.1021/acs.biochem.9b00237). Biochemistry 58:3365–3376. doi:10.1021/acs.biochem.9b00237

All plants, algae and cyanobacteria rely on the Calvin-Benson-Bassham (CBB) cycle for growth. Rubisco is the central enzyme of the CBB cycle and the most abundant enzyme on the planet: it does the tricky bit where CO<sub>2</sub> gets "fixed" onto a soluble sugar. While it is often said that rubisco is "slow," it is actually an average enzyme in terms of "turnover number" (maximum rate per active site, k<sub>cat</sub>). The true rate of rubisco carboxylation is much slower than its k<sub>cat</sub>, however, because rubisco can react non-specifically with O<sub>2</sub>. I certainly think it's surprising that rubisco is not faster or more specific given how important and abundant it is. 

![RuBisCO illustration by David Goodsell](https://cdn.rcsb.org/pdb101/motm/images/two-forms.gif){: .center-image }

What's the deal with rubisco? Why isn't it faster? Why isn't it more CO<sub>2</sub>-specific? People often argue that Rubisco can't be both fast and specific at the same time. Correlations between rubisco kinetic parameters are taken to support this argument since they show that faster Rubiscos (higher k<sub>cat</sub>) are less CO<sub>2</sub>-specific. But these arguments were based on a very small dataset (about 20 rubiscos). We collected a much larger dataset of about 300 rubiscos and found that the correlations are now substantially weaker. 

Our main takeaway from this dataset is that rubisco kinetics display surprisingly little variation. Turnover numbers for most enzymes vary over 5-10 fold but less than twofold for rubisco. Rubisco CO<sub>2</sub>-specificity varies even less - about 30%. Narrow variation suggests tight chemical constraints on rubisco evolution. We offer a coarse-grained model of rubisco catalysis that could explain the constraints imposed on the Rubisco evolution. I think this work should cause us to re-evaluate prospects for Rubisco engineering, since a tightly-constrained enzyme is probably hard to engineer. We put a fair bit of effort into suggesting experiments and engineering strategies that could test our model, so I do hope that someone will try to prove us wrong. 

This work started as a journal club of [Tcherkez et al. PNAS 2006](http://www.pnas.org/content/103/19/7246) and [Savir et al. PNAS 2010](http://www.pnas.org/content/107/8/3475.short) that [Dave Savage](http://www.savagelab.org/) suggested when we visited [Ron Milo's lab](https://www.weizmann.ac.il/plants/Milo/home) in January 2018. [Noam Prywes](https://twitter.com/noamprywes?lang=en) and I scrounged together data for the JC and Uri Moran did a lot of the later heavy lifting, combing the literature for as much Rubisco data as we could find. 