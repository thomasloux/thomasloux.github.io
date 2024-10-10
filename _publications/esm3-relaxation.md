---
title: "Does Structural Information Improve ESM3 for Protein Binding Affinity Prediction?"
collection: publications
category: conferences
permalink: /publication/esm3-structure-relaxation
excerpt: 'This preprint paper is about evaluating the impact of different relaxation strategies on variant structures for mutational binding affinity prediction, using ESM3 as an multimodal encoder.'
date: 2024-12-15
venue: "Accepted at Machine Learning for Structural Biology (MLSB) Workshop, NeurIPS"
#paperurl: 'https://thomasloux.github.io/files/mlsb-submission-loux.pdf'
---

**Abstract** This paper investigates the impact of incorporating structural information into the protein-protein interaction predictions made by ESM3, a multimodal protein language model (pLM). We utilized various structural variants as inputs and compared three widely used structure acquisition pipelines—EvoEF2, Gromacs, and Rosetta Relax—to assess their effects on ESM3’s performance. Our findings reveal that the use of a consistent identical structure, regardless of whether it is relaxed or variant, consistently enhances model performance across various datasets. This improvement is striking in few-show learning. However, performance deteriorates when different relaxed mutant structures are used for each variant. Based on these results, we advise caution when integrating distinct mutant structures into ESM3 and similar models.This study highlights the critical need for careful consideration of structural inputs in protein binding affinity prediction.