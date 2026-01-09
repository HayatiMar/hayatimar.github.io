---
title: "Predicting the short-term success of human influenza virus variants with machine learning"
collection: publications
category: manuscripts
permalink: /publication/2022-08-04-flu_prediction
excerpt: 'This research uses machine learning and phylogenetic tree topology to predict which influenza strains will dominate future seasons, achieving up to 85% accuracy in forecasting viral evolution.'
date: 2022-08-04
venue: 'The Royal Society'
paperurl: 'https://royalsocietypublishing.org/rspb/article/287/1924/20200319/85530/Predicting-the-short-term-success-of-human'
---
## The Challenge: The Moving Target of Vaccine Selection
Seasonal influenza remains a global health priority due to its rapid antigenic drift. For vaccines to be effective, they must match the specific strains that will dominate months after the vaccine is designed. Traditionally, this selection process relies on measuring the "fitness" of emerging variants through genetic surveillance and lab-based assays. However, identifying the "winner" of the evolutionary race in real-time remains a significant challenge.

## The Innovation: Leveraging Tree Topology
Our research introduces a novel machine learning framework that shifts the focus from individual mutations to the structural geometry of evolution. By analyzing the "shape" (topology) of phylogenetic trees, we can identify patterns of rapid growth and diversification before a strain becomes dominant.

- Phylogenetic "Subtrees": Instead of predicting the behavior of single sequences, we analyzed the success of "subtrees"—clusters of closely related viruses.

- Feature Engineering: We trained our models on a combination of:

  -Topological Features: Quantitative measures of tree branching patterns and "balance" that signal early lineage expansion.

  -Genetic Markers: Mutations at known epitope sites (the regions of the virus targeted by the human immune system).

  -Temporal Data: The timing and velocity of lineage emergence.

## Key Results & Performance
Using nearly 40 years of H3N2 data and a decade of H1N1 data, the model demonstrated high predictive power:

Predictive Accuracy: The framework achieved 71–85% accuracy (AUC 0.75–0.90) in forecasting which lineages would expand significantly within a two-year window.

Universal Signatures: A model trained exclusively on H3N2 data performed effectively when tested on H1N1. This suggests that the evolutionary "shape of success" is largely consistent across different influenza subtypes.

Early Detection: The study proved that tree structure contains a detectable signal of fitness that often precedes a variant’s rise to high frequency in the global population.

## Impact & Application
This work provides a computationally efficient tool for genomic surveillance. By integrating these machine learning models into existing WHO surveillance pipelines, health organizations can gain a more objective, data-driven "early warning system" for strain selection, ultimately leading to more effective seasonal vaccines and better public health outcomes.

