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
    #url: "#test-link"
    #btn_label: "Read More"
    #btn_class: "btn--primary"
feature_row3:
  - image_path: ../images/structure.png
    alt: "structure"
    title: "Structural annotations of proteins"
    excerpt: 'Proteins are the most fundamental molecule in the biology. To understand the working of a biological entity, it is important to understand the detailed working of its constituent proteins. A fundamental quest in biology is to elucidate the three dimensional structure of proteins, so as to understand the mechanism of the protein and to allow predicts for the effect of mutations on the working of the protein. Apart from being able to solve the structures using experimental techniques, which could be challenging and time-consuming, a plethora of computational techniques exist that can be used to reasonably predict the structure of certain parts of a protein. Most of these computational methods rely on sequence similarity and homology, and are thus harder to apply in regions of proteins that are not conserved. I am currently developing methods and workflows that can accurately predict such regions using a mixture of sequence and structure based methods. For example, we used this method to accurately [predict the 3D structure of the NBAS protein](https://www.nature.com/articles/s41436-019-0698-4) involved in Infantile Liver Failure Syndrome - 2, allowing collaborators to build a genotype-phenotype map of the disease.'
    #url: "#test-link"
    #btn_label: "Read More"
    #btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include carousel.html height="35" unit="%" duration="6" transition="fade" %}

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
