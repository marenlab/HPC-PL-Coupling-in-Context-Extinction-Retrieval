# Hippocampal-prelimbic coupling during context-dependent extinction retrieval in rats

**Authors**  
Flávio Afonso Gonçalves Mourão¹, Michael S. Totty², Tuğçe Tuna³, Stephen Maren¹⁴*

---

**Affiliations**  
1. Beckman Institute for Advanced Science and Technology, University of Illinois Urbana-Champaign, Urbana, IL  
2. Department of Biostatistics, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD  
3. Institute for Neuroscience, Texas A&M University, College Station, TX  
4. Department of Psychology, University of Illinois Urbana-Champaign, Champaign, IL

DOI:  https://doi.org/10.1002/hipo.70058

---

# Data Processing and Analysis Pipeline

This repository provides the MATLAB-based LFP and behavioral data processing pipeline used in the analyses reported above.
The pipeline was originally developed and validated using datasets from previously published experiments:

DOI: https://doi.org/10.1038/s42003-025-08580-0


---
## LFP Data Processing

This codebase organizes neural and behavioral signals into standardized data structures to support reproducible downstream analyses, including spectral analysis, functional connectivity, and behavior–LFP coupling.

---

## Pre-processing Overview

The pipeline performs the following steps:

- Selects and organizes LFP channels from the medial prefrontal cortex (PL/IL) and hippocampus
- Assumes LFP data were previously extracted and downsampled to 1 kHz
- Defines experimental epochs:
  - Baseline
  - CS (context exposure or tone)
  - ITI
- Aligns freezing and non-freezing behavioral events to neural recordings
- Extracts LFP segments time-locked to behavioral events
- Normalizes hippocampal signal amplitude relative to mPFC
- Outputs standardized data structures for further analysis

---
Author:

**Flavio Mourao**  

**Contact:**  
🧠 Maren Lab – Beckman Institute for Advanced Science and Technology  
   University of Illinois Urbana-Champaign
   
   mourao.fg@illinois.edu  
    
---

**Started:** November 2023  
**Last updated:** April 2025


