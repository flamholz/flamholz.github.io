---
layout: post
title:  "(Relatively) new preprints and publications"
date:   2022-10-18 05:00:00 -0800
published: true
categories: publications
tags: co2-fixation bacteria synbio earth-history elemental-cycles photochemistry
excerpt: Since I last updated this site, I've published a few papers and preprints. Here's quick overview. 
---

Since I last updated this site, I've published a few papers and preprints. I'll eventually integrate these into my [selecta](https://flamholz.github.io/selecta/), but for now a quick overview. 

# Understanding the metabolism of microbial communities

In my postdoc work with [Dianne Newman](https://dknweb.caltech.edu/) and [Rob Phillips](https://www.rpgroup.caltech.edu/), I have been trying to quantify spatiotemporal changes in O<sub>2</sub> concentrations during the growth of bacterial biofilms. The goal is to understand the physical and chemical limits on growth and metabolic rates in spatially-structured environments like biofilms, soils and tissues. Unfortunately, we found that many of the bacteria we study secrete molecules that confound optical quantification of O<sub>2</sub> by existing methods, so we wrote a short report with data documenting the problems. 

Flamholz AI, Saccomano S, Cash K, Newman DK. 2022. [Optical O<sub>2</sub> sensors also respond to redox active molecules commonly secreted by bacteria](https://www.biorxiv.org/content/10.1101/2022.08.08.503264v1). bioRxiv (accepted at mBio).

On the theme of understanding the growth and metabolism of real-world microbial communities, Dianne and I also wrote a "dispatch" ruminating on an excellent paper on [predicting communal denitrification rates from genomes](https://www.sciencedirect.com/science/article/pii/S0092867421015427) by [Karna Gowda](https://karnagowda.github.io/) et al. in [Seppe Keuhn](https://www.kuehnlab.org/) and [Madhav Mani](https://www.madhavmani.com/)'s groups. 

Flamholz AI, Newman DK. 2022. [Microbial communities: The metabolic rate is the trait](https://www.sciencedirect.com/science/article/pii/S096098222200224X?via%3Dihub). Curr Biol 32:R215–R218.

# Synthetic biology to study Earth history

Bridging my PhD and postdoc research, I recently used the [*E. coli* reconstitution of a bacterial CO2 concentrating mechanism](https://elifesciences.org/articles/59882) (CCM) that I developed to study how such a complex, multi-component system could have evolved. I hypothesized that CCM evolution was "catalyzed" by ancient CO<sub>2</sub> levels, which Earth scientists argue (from data) were one much higher than today. I used the reconstitution to show that high-but-decreasing CO<sub>2</sub> would indeed help explain the evolution of bacterial CCMs, which otherwise appear "irreducibly complex." Read the preprint for more detail: 

Flamholz AI\*, Dugan E\*, Panich J, Desmarais JJ, Oltrogge LM, Fischer WW, Singer SW, Savage DF. 2022. [Trajectories for the evolution of bacterial CO2-concentrating mechanisms](https://www.biorxiv.org/content/10.1101/2022.06.21.497102v2). bioRxiv.

I also contributed to a companion paper by my friends Renee Wang and Rob Nichols et alia. We engineered a cyanobacterium expressing a resurrected billion+ year-old rubisco as it's sole carboxylase, measuring the C isotope content of biomass when we grow this strain in a variety of conditions. Earth scientists use isotopic measurements together with physiological models to draw inferences about the CO<sub>2</sub> content of ancient atmosphere from the measured isotopic content of sedimentary rocks. However, the standard models cannot explain the isotopic content of our engineered strain. We offer an explanation for this failure and an alternative model that can explain the data. 

Wang RZ, Nichols RJ, Liu AK, Flamholz AI, Banda DM, Savage DF, Eiler JM, Shih PM, Fischer WW. 2022. [Evolution of Carbon Isotope Fractionation in Cyanobacteria](https://www.biorxiv.org/content/10.1101/2022.06.22.497258v1). bioRxiv.

# Negative catalysis as a mode of early enzyme evolution

When my dear friend and mentor Danny Tawfik died unexpectedly in May 2021, he had just presented this manuscript to his lab. In it, he explored the consequences of a simple observation: some modern enzyme superfamilies share a catalytic mechanism, while others share a non-catalytic binding motif (e.g. they bind phosphates). What could non-catalytic binding have achieved for emerging enzyme families? In simple models of early catalysts, such "uniform binding" - equal stabilization of bound states - cannot produce rate acceleration. Danny proposed that we turn our attention to negative-catalysis, where binding slows a dispreferred solution reaction e.g. by exclusion of water or metal. This mode of catalysis may be especially crucial early in enzyme evolution. It was my privilege to help escort Danny on one last speculation about one of his favorite topics: the early evolution of enzyme catalysis. All the more so because I was able to do so with cherished co-authors. 

Noor E\*, Flamholz AI\*, Jayaraman V\*, Ross BL\*, Cohen Y, Patrick WM, Gruic-Sovulj I, Tawfik DS. 2022. [Uniform binding and negative catalysis at the origin of enzymes](https://onlinelibrary.wiley.com/doi/10.1002/pro.4381). Protein Sci 31.

# Disequilibrium improves information transmission in transcription

Working with Nick Lammers and [Hernan Garcia](http://garcialab.berkeley.edu/), we used information theory and statistical physics to study how energy dissipation (ATP) can be harnessed to improve the performance of model gene regulatory networks. This work was motivated in particular by Nick and Hernan's work on fly development, where fast transmission of information from the local environment (the concentration of transcription factors) to output (transcription and translation of genes important in the next developmental cycle) is critical due to rapid developmental timescales (minutes per cycle). We show that biologically plausible levels of energy input can lead to significant gains information transmission, but the optimal regulatory mechanisms for realizing these gains depend on the "design goals" - limiting noise or maximizing dynamic range - and on context - e.g. the degree of interference from transcription factors outside the network.  

Lammers NC, Flamholz AI, Garcia HG. 2022. [Competing constraints shape the non-equilibrium limits of cellular decision making](https://www.biorxiv.org/content/10.1101/2022.07.01.498451v1.abstract). bioRxiv.


# Human impacts on the Earth system

Griffin Chure, Rachel Banks & co. in [Rob Phillips](https://www.rpgroup.caltech.edu/) group spearheaded an amazing effort to make a Bionumbers for Human impacts on the Earth, the [Human Impacts DB](http://www.anthroponumbers.org/catalog/). We've been using the DB to bring a "[by the numbers](http://book.bionumbers.org/)" perspective to the global environment. 

Chure G, Banks RA, Flamholz AI, Sarai NS, Kamb M, Lopez-Gomez I, Bar-On Y, Milo R, Phillips R. 2022. [Anthroponumbers.org: A quantitative database of human impacts on Planet Earth](https://www.sciencedirect.com/science/article/pii/S266638992200157X?via%3Dihub). PATTERNS.

# Why do cells have so-many similar co-enzymes?

Cells have lots of very similar co-enzymes, especially those participating in redox reactions like NADH and NADPH. Why do they need two? It's common to argue that NADH is "for catabolism" and NADPH is "for anabolism," but how do we know? I had the pleasure of studying this question with [Josh Goldford](https://jgoldford.github.io/). We used metabolic models to ask: what happens if cells had only one nicotinamide co-enzyme? 

Goldford JE, George AB, Flamholz AI, Segrè D. 2022. [Protein cost minimization promotes the emergence of coenzyme redundancy](https://www.pnas.org/doi/full/10.1073/pnas.2110787119). Proc Natl Acad Sci U S A 119:e2110787119.

# eQuilibrator 3.0 and API

In my first project in the Milo lab (≈2010) I worked with with [Elad Noor](https://scholar.google.com/citations?user=E4UymDMAAAAJ&hl=en) to build [eQuilibrator](https://equilibrator.weizmann.ac.il/), an online calculator for estimating the thermodynamic potentials of metabolic reactions. Over the years we have greatly improved the website, and, with the help of several crucial collaborators like Moritz Beber, developed a programmatic API. The API enables modelers to get make arbitrary estimates $\Delta$G estimates without crashing the website, and permits more accurate calculations by giving access to the covariance between related thermodynamic estimates.

Beber ME, Gollub MG, Mozaffari D, Shebek KM, Flamholz AI, Milo R, Noor E. 2021. [eQuilibrator 3.0: a database solution for thermodynamic constant estimation](https://academic.oup.com/nar/article/50/D1/D603/6445959). Nucleic Acids Res.


# COVID adventures

Early in the pandemic I participated in a series of "by the numbers" efforts with my former advisor, [Ron Milo](https://www.weizmann.ac.il/plants/Milo/home), and my current co-mentor [Rob Phillips](https://www.rpgroup.caltech.edu/). These efforts were designed to provide accurate reference for quantitative values relating to the virus and the infection, and to put those numbers in context for scientific and broader audiences. 

1. Bar-On YM, Flamholz A, Phillips R, Milo R. 2020. [SARS-CoV-2 (COVID-19) by the numbers](https://elifesciences.org/articles/57309). Elife 9.
2. Sender R, Bar-On YM, Gleizer S, Bernshtein B, Flamholz A, Phillips R, Milo R. 2021. [The total number and mass of SARS-CoV-2 virions](https://www.pnas.org/doi/full/10.1073/pnas.2024815118). Proc Natl Acad Sci U S A 118.
3. Bar-On YM, Sender R, Flamholz AI, Phillips R. 2020. [A quantitative compendium of COVID-19 epidemiology](https://arxiv.org/abs/2006.01283). arXiv preprint arXiv.

While I was still at Berkeley (through Sept. 2021), I also got involved with an effort between [Jill Banfield](https://nanogeoscience.berkeley.edu/) and [Kara Nelson's](https://ce.berkeley.edu/people/faculty/nelson) groups to quantify COVID incidence by simplifying and lowering the cost of wastewater COVID assays. 

1. Crits-Christoph A, Kantor RS, Olm MR, Whitney ON, Al-Shayeb B, Lou YC, Flamholz A, Kennedy LC, Greenwald H, Hinkle A, Hetzel J, Spitzer S, Koble J, Tan A, Hyde F, Schroth G, Kuersten S, Banfield JF, Nelson KL. 2021. [Genome Sequencing of Sewage Detects Regionally Prevalent SARS-CoV-2 Variants](https://journals.asm.org/doi/10.1128/mBio.02703-20). MBio 12.
2. Greenwald HD, Kennedy LC, Hinkle A, Whitney ON, Fan VB, Crits-Christoph A, Harris-Lovett S, Flamholz AI, Al-Shayeb B, Liao LD, Beyers M, Brown D, Chakrabarti AR, Dow J, Frost D, Koekemoer M, Lynch C, Sarkar P, White E, Kantor R, Nelson KL. 2021. [Tools for interpretation of wastewater SARS-CoV-2 temporal and spatial trends demonstrated with data collected in the San Francisco Bay Area](https://www.sciencedirect.com/science/article/pii/S2589914721000244?via%3Dihub). Water Research X 12:100111.


