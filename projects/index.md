---
title: Research
nav:
  order: 2
  tooltip: Research Introduction
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research

1. Genomic AI for Human Complex Disease

We design and apply AI models to predict gene expression and chromatin accessibility from DNA sequence, enabling a sequence-to-function framework that empowers discovery of:
	•	cis-regulatory elements (CREs) active in specific cell types, including rare ones  ￼
	•	regulatory variants via allele-specific chromatin accessibility (ASCA) and Bayesian fine-mapping of eQTLs  ￼
	•	causal genes underlying complex traits by integrating GWAS, eQTL, and CRE-informed models  ￼
	•	ensemble and reference-level AI models for variant effect prediction across multiple tissues and cell types  ￼
Key applications include biomarker discovery, identification of cell-type-specific drug targets, and the development of interpretable precision medicine frameworks  ￼.

2. Predictive Design of Synthetic Regulatory Circuits in Plants

Building on genomic AI frameworks, we extend our work to plant systems, aiming to control gene expression in a cell-type-specific and developmentally stable manner. Our plant-focused projects include:
	•	Identification of standalone promoters using machine learning to drive targeted expression in rice endosperm and other tissues  ￼
	•	Integration of cell-type-resolved epigenomics (e.g., snATAC-seq) to map native regulatory grammars
	•	Design of synthetic regulatory circuits that balance expression specificity and robustness  ￼
This work lays a foundation for rational engineering of plant traits, bridging the gap between breeding and genetic modification.

3. Single-Cell Multi-Omics and Regulatory Circuit Mapping

We actively generate and analyze single-cell multi-omics data (scRNA-seq, snATAC-seq) from human and plant systems. Our computational pipelines enable:
	•	Discovery of CRE-to-gene maps through integration of chromatin accessibility and transcriptomic profiles
	•	Variant-level modeling of regulatory activity using multi-modal and allele-specific data
	•	Functional prediction of noncoding variants using ensemble AI approaches trained on thousands of cell-type models 

Long-Term Vision

Our ultimate goal is to build interpretable and generalizable AI systems that translate genomic sequences into cellular behavior, phenotypes, and disease risk. We envision our models supporting:
	•	Cell-type-resolved risk interpretation in genome medicine
	•	Synthetic control of gene expression for agriculture and biotechnology
	•	Bridging biology and AI through multimodal data and mechanistic modeling

Collaborations & Funding

We collaborate widely with leading institutions such as Boston Children’s Hospital, University of Michigan, Kyunghee University, and Washington University in St. Louis, contributing to multi-institutional efforts in nephrology, genomics, and plant biotechnology.
 
{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
