# v-phaser2
The v-phaser tool for the analysis of viral NGS data

## Overview
V-Phaser 2 is a tool to call variants in genetically heterogeneous populations from ultra-deep sequence data. It combines information regarding the covariation (i.e. phasing) between observed variants to increase sensitivity and an expectation maximization algorithm that iteratively recalibrates base quality scores to increase specificity. V-Phaser can reliably detect rare variants in diverse populations that occur at frequencies of <1%. V-Phaser 2 is a complete rewrite of the original V-Phaser. It contains a new model for length polymorphisms (indels) and incorporates paired end read information in its phasing model. The data access and probability computation sections of the code have also been highly optimized, resulting in substantial improvements in running time and memory usage.

## Credits
Yang X, Charlebois P, Macalalad A, Henn MR, and Zody MC. (2013) V-Phaser 2.0: Variant Inference for Viral Populations. BMC Genomics 14:674.

## Funding
Support for this tool was provided by the National Institute of Allergy and Infectious Diseases through the Genome Sequencing Center for Infectious Diseases.

See: https://www.broadinstitute.org/scientific-community/science/projects/viral-genomics/v-phaser-2
