---
layout: page
title: Writing
permalink: /selecta/
---

## For Non-Scientist Humans

+ "[Urbanism and Bike Share Maintenance](https://www.berkeleyside.com/2019/11/01/opinion-urbanism-and-bike-share-maintenance-a-review-of-bay-wheels)" a review of the Lyft-owned East Bay bike share service. [Berkeleyside](https://www.berkeleyside.com/2019/11/01/opinion-urbanism-and-bike-share-maintenance-a-review-of-bay-wheels) 10.2019

+ "[Bike Boulevards are Fiction](https://www.berkeleyside.com/2019/05/28/opinion-berkeleys-bike-boulevards-are-fictions)" on the joke that is Berkeley bike infrastructure. [Berkeleyside](https://www.berkeleyside.com/2019/05/28/opinion-berkeleys-bike-boulevards-are-fictions) 5.2019

+ "[An Interview with Geobiologist Woody Fischer](http://hypocritereader.com/69/woody-fischer-interview)" on the transformative effects photosynthesis has wrought on the Earth ecosystem. [The Hypocrite Reader](http://hypocritereader.com/69/woody-fischer-interview) 10.2016

+ "[An Interview with George Fox](http://hypocritereader.com/59/interview-george-fox)" on the evolution of life, the ribosome and the potential for alien inoculation of Earth. [The Hypocrite Reader](http://hypocritereader.com/59/interview-george-fox) 12.2015

## Public Talks & Such

+ "[Understanding the Greenhouse Effect from Classic Experiments](https://www.youtube.com/watch?v=s88fDQM0ycc&t=3s)" on the basic mechanism of the greenhouse effect, which we've understood for over 100 years. [Nerd Night East Bay](https://www.youtube.com/watch?v=s88fDQM0ycc&t=3s) 5.29.2017

## Online Resources

+ "[eQuilibrator](http://equilibrator.weizmann.ac.il/), the Biochemical Thermodynamics Calculator." An online tool for calculating thermodynamic potentials of biochemical reactions using free-text search. Development ongoing with Elad Noor.

+ "[Classic Reactions](http://equilibrator.weizmann.ac.il/static/classic_rxns/classic_reactions/index.html)" - a primer on the basics of metabolism from a thermodynamic perspective. Housed on eQuilibrator and written with help from Elad Noor, Noam Prywes, Dave Savage and Ron Milo. 

+ "[Avi's Faves](https://verse.press/playlist/avis-faves-1195790641368693502)" Poems my friend [Andrew](http://www.andrewbadr.com/) thinks I like. He is mostly right.

## Academic Writing

These are my faves. Find a full listing on [Google Scholar](https://scholar.google.com/citations?user=A7RolPoAAAAJ&hl=en)

### Primary Research

#### "[Revisiting tradeoffs between Rubisco kinetic parameters](https://pubs.acs.org/doi/10.1021/acs.biochem.9b00237)" 

![RuBisCO illustration by David Goodsell](https://cdn.rcsb.org/pdb101/motm/images/two-forms.gif){: .center-image }

All plants, algae and cyanobacteria rely on the Calvin-Benson-Bassham (CBB) cycle for growth. Rubisco is the central enzyme of the CBB cycle and the most abundant enzyme on the planet. It does the tricky bit where CO<sub>2</sub> gets "fixed" onto a soluble sugar. Rubisco is responsible for the vast majority of carbon fixation on Earth. While it is often said that Rubisco is "slow," it is actually an average enzyme in terms of "turnover number" (maximum rate per active site). The true rate of Rubisco carboxylation is much slower than measured, however, because it reacts with O<sub>2</sub> in addition to CO<sub>2</sub>. I certainly think it's surprising that Rubisco is not faster or more specific given how important and abundant it is. 

People often argue that Rubisco can't be both fast and specific at the same time. Correlations between Rubisco’s kinetic parameters are taken to support this argument since they suggest that faster Rubiscos (higher carboxylation turnover numbers) are less CO<sub>2</sub>-specific. But these analyses are based on data from only 20 Rubiscos. We collected a dataset containing recent high-quality measurements of 300 Rubiscos. The interesting correlations are now substantially weakened, which induced us to re-evaluate the mechanistic chemical models that were previously argued to force trade-offs between Rubisco kinetic parameters.

The main takeaway from our much-larger dataset is that Rubisco kinetics display surprisingly little variation. Turnover numbers for most enzymes vary over 5-10 fold but less than twofold for Rubisco. Rubisco CO<sub>2</sub>-specificity varies even less - about 30% among the Form I enzymes (the kind found in plants and cyanobacteria). We think that extremely narrow variation suggests tight chemical constraints on Rubisco evolution and offer a coarse-grained model of Rubisco catalysis that could explain the constraints imposed on the Rubisco evolution. I think this work should cause us to re-evaluate prospects for Rubisco engineering, since a tightly-constrained enzyme is probably hard to engineer. We put a fair bit of effort into suggesting experiments and engineering strategies that could test our model, so I do hope that someone will try to prove us wrong. 

This work started as a journal club of [Tcherkez et al. PNAS 2006](http://www.pnas.org/content/103/19/7246) and [Savir et al. PNAS 2010](http://www.pnas.org/content/107/8/3475.short) that [Dave Savage](http://www.savagelab.org/) suggested when we visited [Ron Milo's lab](https://www.weizmann.ac.il/plants/Milo/home) in January 2018. [Noam Prywes](https://twitter.com/noamprywes?lang=en) and I scrounged together data for the JC and Uri Moran did a lot of the later heavy lifting, combing the literature for as much Rubisco data as we could find. 

#### "[DABs are inorganic carbon pumps found throughout prokaryotic phyla](https://www.nature.com/articles/s41564-019-0520-8)" 

![H. neapolitanus CCM illustration by Rachel Shipps](/assets/hnea_ccm_diagram.png){: .center-image }

When I started my PhD studying the carboxysome based CO2-concentrating mechanism (CCM) found in bacteria, it was unclear if we knew all the genes making up this exquisite system. This variety of CCM is found in proteobacteria and cyanobacteria, but the most recent genetic screens were done in early 1990s and only a few mutants had been mapped. Based on the accumulated data, we thought there were about 15 genes - roughly 10 genes making up the carboxysome and 2-5 genes for inorganic carbon transport. Also, when we started, the proteobacterial transporters had not yet been found. So our goal was to determine (i) whether other genes are required for the CCM and (ii) which genes perform the essential transport activity. 

We were happy to discover that the Arkin and Deutschbauer labs (upstairs from us) had recently developed a simple extension of [TN-Seq](https://en.wikipedia.org/wiki/Transposon_sequencing) called [RB-TNSeq](https://mbio.asm.org/content/6/3/e00306-15.abstract). RB-TNSeq really simplifies whole genome screens of microbes. In the beginning, I had big ambitions. As one does. I was going to do genetic screens in cyanobacteria and proteobacteria, and I was going to do all the work myself! Luckily, [Jack Desmarais](https://twitter.com/Jjdesmarais2) came along and took the lead on this project. We chose to focus on a model proteobacterium, *H. neapolitanus*, because (i) it is relatively closely related to *E. coli*, (ii) we can purify carboxysomes from *H. neapolitanus* and by heterologous expression in [*E. coli*](https://www.pnas.org/content/109/2/478), and (iii) earlier studies had focused on cyanobacterial genetics and so less was known about the proteobacterial system. 

Using RB-TNSeq we mapped 551 essential genes in *H. neapolitanus* and compared the fitness of 70,000 knockout mutants in ambient air - where the CCM is required for growth - and elevated CO2 (where the CCM is dispensable). Comparing fitness in the two conditions identified 17 genes required for CCM function, including all known carboxysome genes (except one), three transcriptional regulators, a putative Rubisco chaperone, and a pair of candidate transporters. Building on [three](https://onlinelibrary.wiley.com/doi/full/10.1111/1462-2920.14090) [recent](https://aem.asm.org/content/85/3/e02096-18) [papers](https://aem.asm.org/content/85/3/e02096-18/article-info) from [Kathleen Scott](http://biology.usf.edu/ib/faculty/kscott/), we showed a pair of genes DabAB2 are both necessary and sufficient for inorganic carbon uptake in our *E. coli* reporter strain. Jack also showed that DabAB2 form a zinc-containing complex in *E. coli*, that the putative zinc-binding resiudes are required, and that the uptake substrate if probably CO2. Altogether we think the data imply pretty strongly that DABs are two-protein complexes that take extracellular CO2 convert it to intracellular bicarbonate using an energy-coupled zinc-based carbonic anhydrase type mechanism. Since DabB proteins are in the same family as diverse cation transporters, we think the energy source is an H+ or Na+ gradient across the membrane, which is pretty impressive since the cation transport protein (where the energy comes from) lives in the membrane and the active site (where the catalysis happens) appears to part of a soluble domain. 

In homage to the open source tradition, we cheekily call these transport complexes DABs for "DABs accumulate bicarbonate." The illustration by Rachel Shipps above gives a rough sense of what we think this complex looks like, though we can only speculate about how it works. Which we do, of course, in [the paper](https://www.nature.com/articles/s41564-019-0520-8). Thanks to Rachel Shipps for her amazing illustrations, Eli Dugan for making so many useful *E. coli* mutants in a pinch, Kelly Wetmore and Morgan Price for much help with RB-TNSeq methods and analysis, Spencer Diamond for the massive upgrade in phylogenetic analysis, and everyone in the Savage lab who pitched in, especially Cissi, Tom, Luke and Allen. 


#### "[pH determines the energetic efficiency of the cyanobacterial CO2 concentrating mechanism](http://www.pnas.org/content/113/36/E5354)" 

![Illustration of a cyanobacterium](/assets/whole_cyano_csome.png){: .center-image }

Cyanobacteria are the ancestors of all oxygenic photosynthesis on the planet and all cyanobacteria have a carboxysome-based CO2 concentrating mechanism (CCM). Many labs are interested in transplanting the cyanobacterial CCM into crop plants in order to improve their growth. Here we show that any reasonable description of the CCM must account for the enormous effect that pH has on the composition of the inorganic carbon pool both inside and outside cells. Once we account for the pH fully, we can produce a mathematical description of the CCM that is consistent with measurements of cyanobacterial physiology and biochemical intuition on multiple levels. A long-term collaboration with [Niall Mangan](http://www.niallmangan.com/) with lots of help from Rachel Hood, Ron Milo and David Savage, [PNAS](http://www.pnas.org/content/113/36/E5354) 2016. 

#### "[Glycolytic strategy as a tradeoff between energy yield and protein cost](http://www.pnas.org/content/110/24/10039)"

![EMP and ED pathways schematic](/assets/emp_ed.png){: .center-image }

Offering a possible thermodynamic explanation for why so many bacteria appear to use non-canonical glycolytic pathways, especially the Entner–Doudoroff (ED) pathway. The textbook Embden-Meyerhoff-Parnass (EMP) pathway yields 2 ATP per glucose while most non-canonical pathways yield less. Naively we'd expect that cells should switch to higher yielding pathways, but they appear not to. Lower yield pathways are more thermodynamically favorable which, we suggest, makes them more suited to carrying high flux. I was incredibly fortunate to collaborate with [Elad Noor](http://www.imsb.ethz.ch/research/sauer/people/eladnoor.html) in this work, with major contributions from Arren Bar-Even, Wolfram Liebermeister and Ron Milo, [PNAS](http://www.pnas.org/content/110/24/10039) 2013. 

Arion Stettner and Daniel Segre wrote a nice commentary on our work [here](http://www.pnas.org/content/110/24/9629.full). This paper - [Fuhrer et al. J. Bac 2005](http://jb.asm.org/content/187/5/1581.abstract) - from the [Sauer lab](http://www.imsb.ethz.ch/research/sauer.html) at ETH was a major motivation for this study. Subsequent to our paper, elegant experiments have shown that the ED pathway is likely present in plants and cyanobacteria ([Chen et al., PNAS 2016](http://www.pnas.org/content/113/19/5441/tab-figures-data)) and is a major route of bacterial degradation of sulfate-substituted sugar acids that derive from plant membranes ([Felux et al., PNAS 2015](https://www.pnas.org/content/112/31/E4298.long)).

### Commentary and Framing

#### "[The Quantified Cell](http://www.molbiolcell.org/content/25/22/3497.full)" 

![Central dogma sizes](/assets/scale_guy.png){: .center-image }

A prelude to [Cell Biology by the Numbers](http://book.bionumbers.org/) on the importance of attaching numbers to biological phenomena, for without them we are just guessing wildly. We use the example of actin-based motility to show how quantitative reasoning can be used to link diverse studies together and draw inferences about cell physiology. We would argue that all hypotheses should be quantified because the process forces you to confront what you do not know and what you cannot reasonably approximate. With Rob Phillips and Ron Milo, [Molecular Biology of the Cell](http://www.molbiolcell.org/content/25/22/3497.full) 9.2014. 

#### "[A note on the kinetics of enzyme action: a decomposition that highlights thermodynamic effects](http://onlinelibrary.wiley.com/doi/10.1016/j.febslet.2013.07.028/full)" 

Pointing out that ideas from non-equilibrium thermodynamics can be used to rewrite a typical Michaelis-Menten enzymatic rate law to include a thermodynamic term expressing the displacement from equilibrium. This functional form has several advantages over the usual Michaelis-Menten framing. First, it accounts for the effect of the "[flux-force relation](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0000144)" where reactions near equilibrium require more enzyme to catalyze the same net flux because much of the enzyme is "wasted" catalyzing the reverse reaction. Second, in the usual Michaelis-Menten form, you must ensure that kinetic parameters are consistent with equilibrium constants (i.e. conform to the Haldane relation). Our strategy "cooks-in" compliance with Haldane by omitting some kinetic constants and instead determining them implicity from the equilibrium constants. Finally, measurements of equilibrium constants are much more available and broadly applicable than measurements of enzymate rate constants, which are gene-specific and often unavailable. Primarily the work of [Elad Noor](http://www.imsb.ethz.ch/research/sauer/people/eladnoor.html) with some help from myself, Wolfram Liebermeister, Arren Bar-Even, and Ron Milo. [FEBS Letters](http://onlinelibrary.wiley.com/doi/10.1016/j.febslet.2013.07.028/full) 2013.

#### "[Rethinking glycolysis: on the biochemical logic of metabolic pathways](https://www.nature.com/articles/nchembio.971)" 

![Favorability of internal e- transfers](/assets/redox_favorability.png){: .center-image }

Explaining how central biochemical constraints limit the space of plausible glycolytic pathways. We consider how toxicitiy and permeability of metabolites as well as chemical feasibility and thermodynamic favorability of enzymatic mechanisms define a very small number of pathways for glucose metabolism (many of which are similar). A nice contribution of this work is the framing of non-oxidative (i.e. fermentative) metabolism as a process of "internal electron rearrangement" where one moiety within a molecule becomes reduced at the expense of oxidizing another. Knowing which of these transfers are favorable can help rationalize many metabolic pathway's structure. I really enjoy using these lines of reasoning in teaching. Primarily the work of [Arren Bar-Even](https://www.mpimp-golm.mpg.de/1926766/Systems-and-Synthetic-Metabolism) with some help from myself, Elad Noor and Ron Milo. [Nature Chemical Biology](https://www.nature.com/articles/nchembio.971) 2012.

