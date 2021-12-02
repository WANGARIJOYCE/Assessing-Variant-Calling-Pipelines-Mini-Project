## Background information
### What is Genetic Variation?
This refers to the difference in the DNA sequences between individuals in a population.

Variations can occur in the germ cells (sperm and egg) or in other body cells( somatic).

Only variations from germ cells can be inherited thus affecting population dynamics and ultimately affecting evolution.

### Types of Genetic Variation
- **Single base-pair substitution**

These are also known as single nucleotide polymorphisms (SNPs) and involve  any nucleic acid substitutions.
They are of two types:

1. Transition
This involves the interchange between purines; between Adenine and Guanine and interchange between pyrimidines; between Cytosine and Thymine

2. Transversion
This involves interchange between a purine and a pyrimidine for example, between Adenine and Cytosine

- **Insertion or deletion (Indels)**

These are classified as small genetic mutations and involve the insertion or deletion of nucleotide bases and can range from two to hundreds of base-pairs in length

- **Structural Variation**

This involves genetic variation that occur over a larger DNA sequence it includes copy number variation and chromosomal rearrangements
common types of structural variations include: deletion, inversion,insertion, duplication, and copy number variation.


### What is Variant calling?
Variant calling is the process by which variants are identified from sequence data.

**Variant calling intuition**

The goal is to obtain a vcf (variant calling format) file that shows variants for all individuals in a given population 

**Intuition**
1. starting point-raw sequences
2. Know where they align
3. Know the genotype for each position
4. look across all samples and determine which sites are variants.

