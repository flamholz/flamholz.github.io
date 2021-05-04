---
layout: page
title: Writing
permalink: /selecta/
---

**Contents**
* TOC
{:toc}

## Public Writing and Talks

+ "[Urbanism and Bike Share Maintenance](https://www.berkeleyside.com/2019/11/01/opinion-urbanism-and-bike-share-maintenance-a-review-of-bay-wheels)" a review of the Lyft-owned East Bay bike share service. [Berkeleyside](https://www.berkeleyside.com/2019/11/01/opinion-urbanism-and-bike-share-maintenance-a-review-of-bay-wheels) 10.2019

+ "[Bike Boulevards are Fiction](https://www.berkeleyside.com/2019/05/28/opinion-berkeleys-bike-boulevards-are-fictions)" on the joke that is Berkeley bike infrastructure. [Berkeleyside](https://www.berkeleyside.com/2019/05/28/opinion-berkeleys-bike-boulevards-are-fictions) 5.2019

+ "[An Interview with Geobiologist Woody Fischer](http://hypocritereader.com/69/woody-fischer-interview)" on the transformative effects photosynthesis has wrought on the Earth ecosystem. [The Hypocrite Reader](http://hypocritereader.com/69/woody-fischer-interview) 10.2016

+ "[An Interview with George Fox](http://hypocritereader.com/59/interview-george-fox)" on the evolution of life, the ribosome and the potential for alien inoculation of Earth. [The Hypocrite Reader](http://hypocritereader.com/59/interview-george-fox) 12.2015

+ "[Understanding the Greenhouse Effect from Classic Experiments](https://www.youtube.com/watch?v=s88fDQM0ycc&t=3s)" on the basic mechanism of the greenhouse effect, which we've understood for over 100 years. [Nerd Night East Bay](https://www.youtube.com/watch?v=s88fDQM0ycc&t=3s) 5.29.2017

## Online Resources

+ "[eQuilibrator](http://equilibrator.weizmann.ac.il/), the Biochemical Thermodynamics Calculator." An online tool for calculating thermodynamic potentials of biochemical reactions using free-text search. Development ongoing with Elad Noor.

+ "[Classic Reactions](http://equilibrator.weizmann.ac.il/static/classic_rxns/classic_reactions/index.html)" - a primer on the basics of metabolism from a thermodynamic perspective. Housed on eQuilibrator and written with help from Elad Noor, Noam Prywes, Dave Savage and Ron Milo. 

+ "[Avi's Faves](https://verse.press/playlist/avis-faves-1195790641368693502)" Poems my friend [Andrew](http://www.andrewbadr.com/) thinks I like. He is mostly right.

## Academic Writing

These are my faves. Find a full listing on [Google Scholar](https://scholar.google.com/citations?user=A7RolPoAAAAJ&hl=en)

### Primary Research

#### "[Functional reconstitution of a bacterial CO<sub>2</sub> concentrating mechanism in *E. coli*](https://elifesciences.org/articles/59882)" 

![Rubisco carboxylation dependent E. coli strain](/assets/ccmb1.png){: .center-image }

Many photosynthetic organisms have evolved CO<sub>2</sub>-concentrating mechanisms (CCMs) that compensate for the relative inefficiencies of CO<sub>2</sub>-fixation by elevating CO<sub>2</sub> levels near the central enzyme of the Calvin cycle, rubisco. Elevated CO<sub>2</sub> is doubly beneficial, bringing rubisco closer to CO<sub>2</sub>-saturation and also excluding O<sub>2</sub> from the active site (explained [here](https://www.cell.com/current-biology/pdf/S0960-9822(20)30120-2.pdf)). CCMs are very significant on the global scale, responsible for perhaps 50% of global photosynthesis. CCMs are also very significant to the organisms harboring them: CCM mutants typically entirely fail to grow in ambient levels of CO<sub>2</sub> (0.04%) and require CO<sub>2</sub> supplementation to enable robust growth (usually 1-5%). In this paper I paid homage to Richard Feynman's famous quote "[What I cannot create I do not understand](https://calisphere.org/item/b3e8d3cb9b8adc01314dba1b1f1fcf84/)" building a bacterial CO<sub>2</sub>-concentrating mechanism from its constituent parts in a non-native host, *E. coli*. You can read more about this work [here](/publications/2020/10/21/functional-reconstitution.html).

#### "[Revisiting tradeoffs between Rubisco kinetic parameters](https://pubs.acs.org/doi/10.1021/acs.biochem.9b00237)" 

![RuBisCO illustration by David Goodsell](https://cdn.rcsb.org/pdb101/motm/images/two-forms.gif){: .center-image }

All plants, algae and cyanobacteria rely on the Calvin cycle for growth. Rubisco is the central enzyme of the cycle and the most abundant enzyme on the planet: it does the tricky bit where CO<sub>2</sub> gets "fixed" onto a soluble sugar. While it is often said that rubisco is "slow," it is actually an average enzyme in terms of "turnover number" (maximum rate per active site, k<sub>cat</sub>). The true rate of rubisco carboxylation is much slower than its k<sub>cat</sub>, however, because rubisco can react non-specifically with O<sub>2</sub>. I certainly think it's surprising that rubisco is not faster or more specific given how important and abundant it is. 

Why isn't rubisco faster? Why isn't it more CO<sub>2</sub>-specific? It's often argued that rubisco can't be both fast and specific. Correlations between rubisco kinetic parameters are taken to support this argument since they show that faster rubiscos are less CO<sub>2</sub>-specific. But these arguments were based on a small dataset (about 20 rubiscos). We collected a much larger dataset and found that most correlations are now substantially weaker, leading to a more nuanced understanding of the factors limiting the evolution of this pivotal enzyme. You can read more about this work [here](/publications/2020/10/21/revisiting-rubisco-tradeoffs.html).

#### "[DABs are inorganic carbon pumps found throughout prokaryotic phyla](https://www.nature.com/articles/s41564-019-0520-8)" 

![H. neapolitanus CCM illustration by Rachel Shipps](/assets/hnea_ccm_diagram.png){: .center-image }

When I started my PhD studying the carboxysome-based CO<sub>2</sub>-concentrating mechanism (CCM) found bacteria, it was unclear if we knew all the genes making up this exquisite photosynthetic adaptation. We thought about 15 genes were involved, but it was conceivable that the number was much higher. Our goal here was to determine (i) whether unknown genes are required for the CCM and (ii) which genes perform the essential inorganic carbon transport activity. Using a barcoded approach to TNSeq called [RB-TNSeq](https://mbio.asm.org/content/6/3/e00306-15.abstract), we investigated 70,000 knockout mutants in the bacterial chemoautotroph, *H. neapolitanus*. We found that at most 17 genes are necessary for this organisms' CCM to function. Building on [three](https://onlinelibrary.wiley.com/doi/full/10.1111/1462-2920.14090) [recent](https://aem.asm.org/content/85/3/e02096-18) [papers](https://aem.asm.org/content/85/3/e02096-18/article-info) from [Kathleen Scott](http://biology.usf.edu/ib/faculty/kscott/), we also showed that a pair of genes - DabAB2 - are necessary and sufficient for inorganic carbon transport. We think the data imply that DABs are two-protein complexes that convert extracellular CO<sub>2</sub> into intracellular HCO<sub>3</sub><sup>-</sup> using an energy-coupled carbonic anhydrase-like mechanism. You can read more [here](/publications/2019/08/12/DABS-are-carbon-pumps.html).

#### "[pH determines the energetic efficiency of the cyanobacterial CO2 concentrating mechanism](http://www.pnas.org/content/113/36/E5354)" 

![Illustration of a cyanobacterium](/assets/whole_cyano_csome.png){: .center-image }

Cyanobacteria are the ancestors of all oxygenic photosynthesis on the planet and all cyanobacteria have a carboxysome-based CO2 concentrating mechanism (CCM). Many labs are interested in transplanting the cyanobacterial CCM into crop plants in order to improve their growth. Here we show that any reasonable description of the CCM must account for the enormous effect that pH has on the composition of the inorganic carbon pool both inside and outside cells. Once we account for the pH fully, we can produce a mathematical description of the CCM that is consistent with measurements of cyanobacterial physiology and biochemical intuition on multiple levels. A long-term collaboration with [Niall Mangan](http://www.niallmangan.com/) with lots of help from Rachel Hood, Ron Milo and David Savage, [PNAS](http://www.pnas.org/content/113/36/E5354) 2016. 

#### "[Glycolytic strategy as a tradeoff between energy yield and protein cost](http://www.pnas.org/content/110/24/10039)"

![EMP and ED pathways schematic](/assets/emp_ed.png){: .center-image }

Offering a possible thermodynamic explanation for why so many bacteria appear to use non-canonical glycolytic pathways, especially the Entner–Doudoroff (ED) pathway. The textbook Embden-Meyerhoff-Parnass (EMP) pathway yields 2 ATP per glucose while most non-canonical pathways yield less. Naively we'd expect that cells should switch to higher yielding pathways, but they appear not to. Lower yield pathways are more thermodynamically favorable which, we suggest, makes them more suited to carrying high flux. I was incredibly fortunate to collaborate with [Elad Noor](http://www.imsb.ethz.ch/research/sauer/people/eladnoor.html) in this work, with major contributions from Arren Bar-Even, Wolfram Liebermeister and Ron Milo, [PNAS](http://www.pnas.org/content/110/24/10039) 2013. 

Arion Stettner and Daniel Segre wrote a nice commentary on our work [here](http://www.pnas.org/content/110/24/9629.full). This paper - [Fuhrer et al. J. Bac 2005](http://jb.asm.org/content/187/5/1581.abstract) - from the [Sauer lab](http://www.imsb.ethz.ch/research/sauer.html) at ETH was a major motivation for this study. Subsequent to our paper, elegant experiments have shown that the ED pathway is likely present in plants and cyanobacteria ([Chen et al., PNAS 2016](http://www.pnas.org/content/113/19/5441/tab-figures-data)) and is a major route of bacterial degradation of sulfate-substituted sugar acids that derive from plant membranes ([Felux et al., PNAS 2015](https://www.pnas.org/content/112/31/E4298.long)).

### Commentary and Framing

#### "[Cell biology of photosynthesis over geologic time](https://www.sciencedirect.com/science/article/pii/S0960982220301202)" 

![Geologic time and the evolution of photosynthesis](/assets/geo_time.png){: .center-image }

Though atmospheric CO<sub>2</sub> concentrations are today [rising precipitously](https://keelingcurve.ucsd.edu/), geologic processes like rock weathering have, over billion-year timescales, led to substantial reductions in atmospheric CO<sub>2</sub>. At the same time, the emergence of oxygenic photosynthesis led to a build up of O<sub>2</sub> in Earth's atmosphere, which is problematic for organisms relying on rubisco to fix carbon. In this primer, [Patrick Shih](http://shih-lab.ucdavis.edu/) and I reflect on how these two trends might have conspired to promote the evolution of novel photosynthetic physiologies (several types of CO<sub>2</sub> concentrating mechanisms) that enable photosynthetic organisms to cope with low levels of the growth substrate (CO<sub>2</sub>) and high levels of inhibitor (O<sub>2</sub>). We describe how these physiologies differ between photosynthetic bacteria, algae and land plants and suggest that these differences might not be coincidental (i.e. no "frozen accident"). 

#### "[The Quantified Cell](http://www.molbiolcell.org/content/25/22/3497.full)" 

![Central dogma sizes](/assets/scale_guy.png){: .center-image }

A prelude to [Cell Biology by the Numbers](http://book.bionumbers.org/) on the importance of attaching numbers to biological phenomena, for without them we are just guessing wildly. We use the example of actin-based motility to show how quantitative reasoning can be used to link diverse studies together and draw inferences about cell physiology. We would argue that all hypotheses should be quantified because the process forces you to confront what you do not know and what you cannot reasonably approximate. With Rob Phillips and Ron Milo, [Molecular Biology of the Cell](http://www.molbiolcell.org/content/25/22/3497.full) 9.2014. 

#### "[A note on the kinetics of enzyme action: a decomposition that highlights thermodynamic effects](http://onlinelibrary.wiley.com/doi/10.1016/j.febslet.2013.07.028/full)" 

Pointing out that ideas from non-equilibrium thermodynamics can be used to rewrite a typical Michaelis-Menten enzymatic rate law to include a thermodynamic term expressing the displacement from equilibrium. This functional form has several advantages over the usual Michaelis-Menten framing. First, it accounts for the effect of the "[flux-force relation](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0000144)" where reactions near equilibrium require more enzyme to catalyze the same net flux because much of the enzyme is "wasted" catalyzing the reverse reaction. Second, in the usual Michaelis-Menten form, you must ensure that kinetic parameters are consistent with equilibrium constants (i.e. conform to the Haldane relation). Our strategy "cooks-in" compliance with Haldane by omitting some kinetic constants and instead determining them implicity from the equilibrium constants. Finally, measurements of equilibrium constants are much more available and broadly applicable than measurements of enzymate rate constants, which are gene-specific and often unavailable. Primarily the work of [Elad Noor](http://www.imsb.ethz.ch/research/sauer/people/eladnoor.html) with some help from myself, Wolfram Liebermeister, Arren Bar-Even, and Ron Milo. [FEBS Letters](http://onlinelibrary.wiley.com/doi/10.1016/j.febslet.2013.07.028/full) 2013.

#### "[Rethinking glycolysis: on the biochemical logic of metabolic pathways](https://www.nature.com/articles/nchembio.971)" 

![Favorability of internal e- transfers](/assets/redox_favorability.png){: .center-image }

Explaining how central biochemical constraints limit the space of plausible glycolytic pathways. We consider how toxicitiy and permeability of metabolites as well as chemical feasibility and thermodynamic favorability of enzymatic mechanisms define a very small number of pathways for glucose metabolism (many of which are similar). A nice contribution of this work is the framing of non-oxidative (i.e. fermentative) metabolism as a process of "internal electron rearrangement" where one moiety within a molecule becomes reduced at the expense of oxidizing another. Knowing which of these transfers are favorable can help rationalize many metabolic pathway's structure. I really enjoy using these lines of reasoning in teaching. Primarily the work of [Arren Bar-Even](https://www.mpimp-golm.mpg.de/1926766/Systems-and-Synthetic-Metabolism) with some help from myself, Elad Noor and Ron Milo. [Nature Chemical Biology](https://www.nature.com/articles/nchembio.971) 2012.
