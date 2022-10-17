---
layout: post
published: false
title:  "#AviLovesYourPaper #1 - Jinich et al. PNAS 2020"
date:   2021-01-15 11:00:00 -0800
categories: twitter papers review
tags: ecology interactions growth length-scale
mathjax: true
excerpt: This week on &#35;AviLovesYourPaper I re-read ...
---

Finally getting to #AviLovesYourPaper #2 on "Short-range interactions govern the dynamics and functions of microbial communities" by @Alma_DalCo. Better late than never. Here we go! https://pubmed.ncbi.nlm.nih.gov/32042125/

Out there in nature (i.e. not on Twitter), species are very often interdependent. 

The most-cited macroscopic example is probably the symbiosis between clownfish and sea anemones. Anemones stinging tentacles provide shelter from predators while the fish cleans the anemones and provides nutrients in its waste. https://en.wikipedia.org/wiki/Amphiprioninae#Symbiosis_and_mutualism

Plants also depend heavily on bacteria and fungi, who help them acquire mineral nutrients like iron and phosphorus. These microbes are capable of some amazing chemical trickery - extracting atoms from rocks - that plants don't do quite as well. https://www.nature.com/scitable/knowledge/library/plant-soil-interactions-nutrient-uptake-105289112/

To court these bugs, plants secrete sugars and other molecules that bacteria & fungi like to eat. You scratch my back etc. https://www.nature.com/scitable/knowledge/library/the-rhizosphere-roots-soil-and-67500617/

In the era of "affordable" DNA sequencing (ahem), we now have hundreds of thousands of complete bacterial genomes for species from many different environments. From oceans, soils, abandoned mines, human poops, dog poops, fish poops, you see the pattern. 

When we inspect these genomes, it looks like many bacteria are missing genes needed to synthesize some of the 20 amino acids that make up proteins. https://pubmed.ncbi.nlm.nih.gov/24910088/

The implication being that, like us humans, who need to eat the 9 amino acids our bodies can't synthesize, these bacteria need to find various amino acids in their environment. Otherwise they will eventually be unable to make new proteins and die. 

Suppose some soil bacterium "X. bacterialis" can't make the amino acid proline. Where would it get proline from? Presumably from other bacteria that *can* make proline. 

Indeed, a teaspoon of soil might contain as many as *a million distinct bacterial species*, many of which will be able to make proline and will unavoidably leak it into the environment as they grow and die. https://bionumbers.hms.harvard.edu/bionumber.aspx?id=100552

So along come @Alma_DalCo et alia with a lovely question: in such fabulously dense bacterial communities, over what distance can amino acids and other small molecules be shared? 

To pursue this question, @Alma_DalCo used two E. coli strains, one that can't make proline (DP) and another that can't make tryptophan (DT). Beyond their metabolic deficiencies, these strains are also labeled with fluorescent proteins to distinguish them on the micrscope.

[pic]

So what happens when these two strains are grown together? If the cells are not motile, asexual bacterial reproduction will lead to nearby cells being closely related and sharing the same metabolic deficiency or "amino acid auxutrophy" in the jargon. 

Proline-deficient DP cells that are surrounded by relatives are also far from  tryptophan-deficient DT cells (that *do* make proline) and will grow poorly for lack of proline. 

[pic]

If fast growth is the goal, the two strains should be interspersed so that most cells receive the amino acids they need. But clonal growth "demixes" the cells (causes clumping) and so some cells will inevitably be far from a source of proline (or tryptophan). 

These "far" cells will grow slowly (or not at all) for lack of proline. What is the relationship between distance and growth? Given this clever setup, this relationship can be measured by watching cells grow on the microscope.

[pic]

As expected, the farther DP cells are from proline-producing (tryptophan-deficient) DT cells, the more slowly they grow. 

[pic]

This relationship can be phrased quantitatively by asking: over what distance does the mixture of cells (e.g. 40% DP, 60% DT) best correlate with the growth rate for each cell type. 

Now you might expect that this number, the "interaction range", would be the same for both amino acids. They are, after all, fairly similar molecules in terms of size, charge and diffusion coefficients in the scheme of things. 

But this not the case. Rather, from Alma's measurements we learn two illuminating things. First, the interaction range is very short, less than 15 cell-lengths for both amino acids, and differs by a factor of 4 between the two (≈3 microns for proline and ≈12 for tryptophan).

Why are proline and tryptophan so different in this regard? The remainder of the paper is dedicated to using a physical model of coupled growth, diffusion and amino acid uptake to advance the idea that these molecules are different because E. coli needs them to different degrees. 

[pic model]

Indeed, E. coli proteins contain about 4x more proline than tryptophan across a range of growth conditions, consistent with the 4x difference in interaction range. https://europepmc.org/article/MED/10099424 

The model advanced by @Alma_DalCo and friends goes like this: when cells are crowded together, they will leak nutrients (e.g. proline) in all directions. So the amount of proline a single cells "sees" depends mostly on how much proline the surrounding cells are taking up. 

[pic linear dep]

For this reason, we should expect the interaction range to be shorter when the uptake rate is higher, as it should be for proline because E. coli needs more proline than tryptophan to make its proteins. 

When interaction ranges are this short, on the order of 10 cell lengths, we expect that many cells will be isolated from key nutrients (proline in this example) and will grow very slowly. 

When the strains grow in clusters apart from each other, this effect should substantially lower the over all growth rate. By simulating different arrangements of cells, Alma et al show that mixing the cells up produces faster growth.

[pic mix it up]

Now my friend Morgan Price would probably accost me (verbally, gently) if I didn't circle back to the point of I made above about many bacteria being unable to make all 20 amino acids. http://morgannprice.org/

Morgan would say that this is an inferrence from sequenced genomes that relies on the assumption that we really know all the pathways by which amino acids are synthesized. Morgan's recent paper shows that this is just wrong. https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1007147

In their recent work, Morgan and colleagues tested 24 bacteria, 12 of which were predicted to be amino acid auxotrophs, i.e. unable to make one amino acid or another based on their genomes. But 23 of 24 grew in minimal medium without any added amino acids!

Morgan & co-authors even go so far as to claim that "Most free-living bacteria can synthesize all 20 amino acids" which truly strikes at the heart of the current dogma in microbiology. 

Perhaps I can offer some synthesis of Morgan and @Alma_DalCo? Maybe most bacteria can indeed make most amino acids as they can't rely on getting them from the environment because "short-range interactions govern the dynamics and functions of microbial communities" /fin


