---
layout: post
title: "Evolutionary Mismatches"
author: "JS"
categories: science
tags: []
image: pvs_evo.jpg
---
### A fun little "side" project

Often, there are discussions around what is the best way to create a phylogeny to capture the evolution of say, a genera. Do you use a single gene as a marker, or concatenate genes together, or some other technique?
\
Viruses, especially small ones, are great to work with from a bioinformatics standpoint - genomes are not insanely large, minimizing complexity/computational resources, and are widely available in sequencing data etc. My thesis revolves around one of these viruses - the _Papillomaviridae_ (PV) family to be precise - using them as a sort of pilot experiment for Logan[add link]. 
\
In the PV field, species are demarcated by their L1 gene, which codes for the major capside protein. This gene is quite nice as far as marker genes go, as they are composed of high conserved, comon structures. Hence, I have been using this gene to do my accounting of PV diversity - if something is more than 10% different in terms of nucleic acid identities, then it counts as a new "species" - or at least creates an arbitrary unit in which to compare everything against evenly.
\
This works great, in the case where a full genome, or at least the L1 + some other gene of interest is found, as it creates an anchor to which you can "assign" these sequences to. However, real life is not quite as neat, and you get cases of "no L1 + lots of other genes".
\
So, how do you then characterize these orphan genes? I suppose it doesnt really matter in the grander picture of recording diversity, but it is important from the perspective of: "If we see one of these orphan sequences, what are the chances that it belongs to the equivalent of a new species (and thus represents some new diveristy that had not previously been described)?". Especially pertinent in the type of testing that we are doing now, 