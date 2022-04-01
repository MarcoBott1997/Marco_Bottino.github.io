---
title: "SARS-CoV-2 variants classification and characterization"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'The idea of this work is to automatize the process of analysis and description of the SARS-CoV-2 virus starting from a sample of its genome and to be able to assign a group of samples to the correct variant. By using a clustering algorithm, in the end, it’s also possible to distinguish a new variant and obtain a description of its most common mutations.'
date: 2022-03-22
venue: 'Proceedings of 14th International Conference on Bioinformatics and Computational Biology'
paperurl: '	https://doi.org/10.29007/5qpk'
citation: 'Sofia Borgato, Marco Bottino, Marta Lovino, and Elisa Ficarra (2022). &quot; SARS-CoV-2 variants classification and characterization &quot; <i>Proceedings of 14th International Conference on Bioinformatics and Computational Biology</i>.'
---
As of late 2019, the SARS-CoV-2 virus has spread globally, giving several variants
over time. These variants, unfortunately, differ from the original sequence identified in
Wuhan, thus risking compromising the efficacy of the vaccines developed. Some software
has been released to recognize currently known and newly spread variants. However, some
of these tools are not entirely automatic. Some others, instead, do not return a detailed
characterization of all the mutations in the samples. Indeed, such characterization can be
helpful for biologists to understand the variability between samples. <br/>
This paper presents
a Machine Learning (ML) approach to identifying existing and new variants completely
automatically. In addition, a detailed table showing all the alterations and mutations found
in the samples is provided in output to the user. SARS-CoV-2 sequences are obtained from
the GISAID database, and a list of features is custom designed (e.g., number of mutations
in each gene of the virus) to train the algorithm. The recognition of existing variants is
performed through a Random Forest classifier while identifying newly spread variants is
accomplished by the DBSCAN algorithm. Both Random Forest and DBSCAN techniques
demonstrated high precision on a new variant that arose during the drafting of this paper
(used only in the testing phase of the algorithm). Therefore, researchers will significantly
benefit from the proposed algorithm and the detailed output with the main alterations of
the samples.<br/>
The tool is freely available [here](https://github.com/sofiaborgato/-SARS-CoV-2-variants-classification-and-characterization), whereas the paper can be downloaded [here](http://marcobott1997.github.io/files/SARS-CoV-2_variants_classification_and_characterization.pdf).
