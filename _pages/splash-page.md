---
title: "Splash Page"
layout: splash
title: "Welcome"
author_profile: true
permalink: /

intro: 
  - excerpt: '<br/><br/>Welcome to my website! I am a Computational Biologist working  at the intersection of Protein Structure, Evolutionary Biology and Phylogenetics. This website contains my major research directions and achievements. Cheers!'
#feature_row:
#  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
#    alt: "placeholder image 1"
#    title: "Placeholder 1"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
#    alt: "placeholder image 2"
#    title: "Placeholder 2"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
#  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
#    title: "Placeholder 3"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: ../images/og_pa_tree_big.png
    alt: "phylogeny"
    title: "Evolutionary history of biological functions"
    excerpt: 'Throughout my research career, I have been interested in tracing the evolutionary history of major biological functions. This is also one of the major central questions of Evolutionary Biology. Given the burst of genomic and proteomic information that is available in public repositories such as NCBI and UniProt, we are in an opportune era where one can trace the detailed evolutionary histories of major biological functions by using principles of Orthology, Phylogenetics and Molecular Evolution. For instance, in my PhD work, I traced the [evolutionary history of wobble base pairing in bacteria](https://academic.oup.com/mbe/article/35/8/2046/5017355) and discovered the dynamic evolution of the major enzymes involved in this process. I also found several other genomic correlates that reflect the evolutionary history of these proteins. In my current work, I am now focusing on tracing the evolutionary history of many major functions across the entire tree of life.'
    #url: ""
    #btn_label: "Read More"
    #btn_class: "btn--primary"
feature_row3:
  - image_path: ../images/structure.png
    alt: "structure"
    title: "Impact of mutations on protein function"
    excerpt: 'Proteins are the most fundamental molecule in biology as any perturbations to these molecules lead to the improper functioning of the biological entity. A fundamental quest in biology is to elucidate the impact of different kinds of changes in the amino acid sequence of proteins on the three-dimensional structure and thereby function of the protein. A plethora of computational methods exist which use experimentally determined strucutres and computationally derived models to try and answer this fundamental question. This field of variant interpretation may also be boosted by the availability of highly accurate computational models courtesy of [AlphaFold](https://alphafold.ebi.ac.uk/). However, recently [we noted and reported that the impact of these models may be lesser than anticipated](https://www.sciencedirect.com/science/article/pii/S0022283621004137). Thus, falling short of solving the three-dimensional structures of thousands of proteins and their respective variants, my aim is to develop a framework that uses the already available structural data (experimental and modelled) to infer how mutations may impact protein structure and function. A useful outcome of this exercise would the ability to build genotype-phenotype maps of genetic disorders, as exemplified by our efforts in [predicting the 3D structure of the NBAS protein](https://www.nature.com/articles/s41436-019-0698-4) involved in Infantile Liver Failure Syndrome - 2.'
    #url: ""
    #btn_label: "Read More"
    #btn_class: "btn--primary"
feature_row4:
  - image_path: ../images/scatter.png
    alt: "scatterplot"
    title: "Biological Data Analysis"
    excerpt: 'The amount of data available today is tremendous for almost every aspect of human life. In the same vein, the massive amount of data available through biological observations and experiments requires further analysis to gain insights. While most sources that generate these data are focused on analysing the data for their own purposes, my goal is to compare and analyze such data from different sources to derive a more general understanding of a biological phenomenon. For instance, I am currently analysing large scale proteomics datasets from a variety of organisms to come up with a metric that measures the difficulty proteins face while folding during the conditions of the experiment. These measures then would give an idea about whether certain proteins are particularly notorious while being handled in the laboratory, and if there is a way in which these could be handled more easily.'
    #url: ""
    #btn_label: "Read More"
    #btn_class: "btn--primary"
---

{% include carousel.html height="35" unit="%" duration="6" %}

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}
