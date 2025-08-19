---
permalink: /Projects/
---

### Why drug synergy?

Drug combinations are at the core of modern therapeutic strategies. Many diseases, especially cancer, are too complex to be effectively treated with a single drug. Combinations allow us to increase efficacy, reduce resistance, and lower toxicity by targeting multiple pathways simultaneously.  

---

### 1. Drug synergy prediction (main)

The majority of potential drug pairs remain untested experimentally, making computational prediction essential. My main project focuses on predicting drug synergy by integrating **DrugCombDB synergy scores** (ZIP, Bliss, Loewe, HSA) with **LINCS L1000 transcriptomic perturbation signatures**.  

The goal is to build **machine learning and deep learning models** that can generalize to unseen drug pairs, leveraging:  
- **Drug features** (SMILES, molecular fingerprints, targets, pathways, MoAs)  
- **Transcriptomic features** (drug-induced perturbation profiles, basal cell-line expression when available)  
- **Network features** (PPI topology, pathway overlap)  

This model will not only prioritize combinations for experimental validation but also provide biological interpretability by highlighting shared targets, pathways, and expression signatures that drive synergy.  
