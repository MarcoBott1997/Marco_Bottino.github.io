---
title: "SARS-CoV-2 variants classification and characterization"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-03-22
venue: 'Proceedings of 14th International Conference on Bioinformatics and Computational Biology'
paperurl: '	https://doi.org/10.29007/5qpk'
citation: 'Sofia Borgato, Marco Bottino, Marta Lovino, and Elisa Ficarra (2022). &quot; SARS-CoV-2 variants classification and characterization &quot; <i>Proceedings of 14th International Conference on Bioinformatics and Computational Biology</i>. 1(1).'
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
The tool is freely available [here] (https://github.com/sofiaborgato/-SARS-CoV-2-variants-classification-and-characterization).
Download paper [here](https://doi.org/10.29007/5qpk)
