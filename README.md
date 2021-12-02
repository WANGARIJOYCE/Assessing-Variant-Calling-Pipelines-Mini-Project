# Assessing-Variant-Calling-Pipelines-Mini-Project
## Overview
This mini-project involves Assessing various variant calling pipelines inorder to come up with an optimized/standardized variant calling pipeline for analyzing insect and pathogen data.


## Contributors
- Allan Okeyo
- Joyce Wangari

## Mentors
- Dr. Caleb Kibet
- Ruth Nanjala
- Andrew Espira
- Hebrew Simon
- Rose Wambui

## Vision
To design a standard variant calling pipeline that is effective and reliable for analyzing insect and pathogen data, that will be adopted across various regions of the world.

## Mission
To evaluate existing varinat calling pipelines, fill in existing gaps and modify the pipelines to suit anlysis of insect and pathogen data.


## Evaluation criteria

- How easy are they to set up and use? Do they provide accessible documentation and tutorials?
- Are they fast and easily scalable based on available compute resources?
- Can they scale to the cloud?
- Can they be used on a variety of data, including insects, pathogens and microbes (virus and bacteria)
- Are they implemented in the latest specifications and versions of the tools? For example, Whether the pipeline implements Nextflow DSL2 syntax and docker or singularity containers
- Are they well and regularly maintained? When were they updated last?




## Background information
### What is Genetic Variation?
- This refers to the difference in the DNA sequences between individuals in a population.
- These are specific regions within a genome that differ between genomes.
- They occur both in the germ cells (sperm and egg) and body cells(somatic).
- Germline variations are of more importance relative to somatic varince since germline variations can be inherited to successive generations affecting population dynamics and ultimately population evolution.

### Types of Genetic Variation

  #### 1. Single Base pair substitution
  
- These are also known as single nucleotide polymorphisms (SNPs) and involve one nucleic acid variation at a specific locus on a genome/chromosome.
- They can be used to predict how an individual would respond to drugs of a particular class, susceptibilty to certain environmental stimulus and well predisposal to certain diseases
- Also, they can be helpful in tracking inheritable of disease genes within a family.
- They are of two types:

 **Transition**; This involves the interchange between purines; between Adenine and Guanine and interchange between pyrimidines; between Cytosine and Thymine

 **Transversion**; This involves interchange between a purine and a pyrimidine for example, between Adenine and Cytosine

  #### 2. Insertion or deletion (Indels)
- These are classified as small genetic mutations and involve the insertion or deletion of nucleotide bases and can range from two to hundreds of base-pairs in length

 #### 3. Structural Variation

- This involves genetic variation that occur over a larger DNA sequence it includes copy number variation and chromosomal rearrangements
common types of structural variations include: deletion, inversion,insertion, duplication, and copy number variation.

  ##### Copy Number Variation
 - These are variations in the DNA that affects a large chank of the DNA, leading to repeats of some sections of DNA. 
 - Can occur as a result of duplication or deletion events in the DNA sequence. 
 - Are of importance in determining disease phenotype and population diversity


 ### What is Variant calling?
Variant calling is the process by which variants are identified from sequence data.

  #### Variant calling intuition

The goal is to obtain a vcf (variant calling format) file that shows variants for all individuals in a given population 

  ##### Intuition
1. starting point-raw sequences
2. Know where they align
3. Know the genotype for each position
4. look across all samples and determine which sites are variants.

[Here](https://github.com/WANGARIJOYCE/Assessing-Variant-Calling-Pipelines-Mini-Project/issues/4) is a link to our project road map
