# Experimental Results: VAT Chain Transaction Solver using LLMs and Knowledge Graphs

This repository contains the experimental results for the research paper:

**Using Large Language Models and Knowledge Graphs for Deciding VAT Chain-Transaction Cases in Austrian Tax Law**  
*Author: Lukas Knogler (Austria, Johannes Kepler University Linz)*

## Overview

In this project, we explore the application of large language models (LLMs) and knowledge graphs to resolve complex VAT chain-transaction cases, specifically within the context of Austrian tax law.

## Contents

The repository includes:

- Results and outputs from various experiments conducted as part of the research.
- Supporting files and data representations used in evaluating LLM-based approaches.

> **Note:**  
> Some data had to be censored to comply with data protection regulations. The original, uncensored data is available through the official sources referenced in the paper.

## Experimental setup

1. Set up a Neo4j Aura Instance
2. Set up a LLM Platform (we used Langsmith from Langhchain)
3. Access the code repository and follow the installation guide
4. Use the provided cases (column 'inputs_decoded' in Results_censored.xslx)
5. Access the original data sources for censored cases
6. Run the script from the code repository
7. Compare columns 'identified_movable_supply' and 'sample_solution_movable_supply' for cases where result is 'Check manually'
8. Make sure to exclude cases according to the evaluation guideline
9. Only use correct represented cases (correct KG) for the application of law-based rules
10. Calculate accuaracy (Correct/Total - Excluded)

## Citation

If you use or reference this work, please cite the original paper:

Lukas Knogler, "Using Large Language Models and Knowledge Graphs for Deciding VAT Chain-Transaction Cases in Austrian Tax Law", JKU Linz, Austria.


## Contact

For questions or collaborations, please contact:  
📧 knogler.lukas@gmail.com

## Related Work

This repository is part of the research project:

**Using Large Language Models and Knowledge Graphs for Deciding VAT Chain-Transaction Cases in Austrian Tax Law**  
*Author: Lukas Knogler, Austria (JKU Linz)*  
See the [code repository](https://github.com/knolukas/chain-transaction-solver.git) for more.

