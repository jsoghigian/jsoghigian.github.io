---
layout: page
title: Code Snipets
permalink: /code/
---

Below are links to scripts or repositories of scripts I have used in analyses.  Most are under continual development.  See repositories for more information.

<div><a href="https://github.com/jsoghigian/vector-eco-evo/blob/master/phylo_anova.R"><img style="vertical-align:middle" height="35px" width="35px" src="https://cdn.rawgit.com/jsoghigian/jsoghigian.github.io/3e9b0a7e/Download_alt_font_awesome.svg"></a>
  <span style=""><a href="https://github.com/jsoghigian/vector-eco-evo/blob/master/phylo_anova.R"> Phylogenetic analysis of variance R code</a></span></div>  
As part of my analysis finding convergent evolution in container specialization in the genus *Aedes*, I wrote a wrapper script that would perform phylogenetically-informed analysis of variance given several models of evolution.  
<br>  
<div><a href="https://github.com/jsoghigian/usco_align"><img style="vertical-align:middle" height="35px" width="35px" src="https://cdn.rawgit.com/jsoghigian/jsoghigian.github.io/3e9b0a7e/Download_alt_font_awesome.svg"></a><span style=""> <a href="https://github.com/jsoghigian/usco_align">USCO Align</a></span></div>  

A set of scripts that take a list of results directories from [BUSCO analyses](http://busco.ezlab.org/), finds orthologs present in all analyses, outputs orthologs present in some threshold of genomes, aligns all orthologs, and outputs a concatenated multisequence alignment file in Phylip and Nexus formats, with a RAxML partition file and Nexus in file partition scheme.
