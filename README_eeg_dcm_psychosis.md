
# 🧠 Investigating Neural Connectivity in Psychosis

**Dynamic Causal Modeling with EEG Biomarkers and Biotype-Specific Analyses**  
*MRes Brain Sciences Thesis Project @ University College London (UCL)*  
*Supervisor: Dr. Rick Adams | Collaborator: Julia Rodriguez Sanchez*

---

## 🧭 Overview

This project explores how **resting-state EEG data** can be used to investigate **neural connectivity patterns and excitation/inhibition (E/I) balance** in psychosis. Using data from the **Bipolar-Schizophrenia Network on Intermediate Phenotypes (B-SNIP)** consortium, we analyzed spectral and source-level signals, and used **Dynamic Causal Modeling (DCM)** to identify patterns across neurobiologically-defined **biotypes** of psychosis.

---

## 🧠 Key Aims

- Characterize frequency-specific power spectral and topographic patterns across psychosis subgroups.
- Use DCM to estimate neural circuit parameters and assess excitation/inhibition balance.
- Simulate biologically informed DCM models to explore connectivity alterations by biotype.
- Evaluate whether EEG biomarkers can distinguish **Biotype 1, Biotype 2, Biotype 3**, and controls.

---

## 🗂️ Repository Contents

```
📁 code/       – MATLAB scripts for EEG preprocessing, spectral analysis, and DCM modeling
📁 poster/     – Final academic poster (PDF) summarizing results
📁 report/     – Final written report / thesis (PDF)
📁 results/    – Figures and plots (e.g. topographic maps, PSD plots, DCM diagrams)
📄 README.md   – Project summary and structure (this file)
```

---

## 🧪 Methods

- **EEG Preprocessing**: Filtering, re-referencing, artifact rejection
- **Spectral Analysis**: Power Spectral Density (PSD) across groups
- **Source Localization**: Reconstructed source activity using SPM12 and canonical cortical coordinates
- **DCM Modeling**: Canonical Microcircuit (CMC) model to simulate neural circuits
- **Simulation**: Used biologically plausible priors to generate predicted EEG responses for each biotype

---

## 📊 Selected Results

- Biotype 1 showed **increased delta and theta power**, consistent with cortical disinhibition.
- Biotype 2 exhibited **reduced gamma** activity, possibly linked to NMDA hypofunction.
- DCM simulations highlighted **distinct alterations in connectivity and synaptic gain** across biotypes.

*(See full figures in `results/` folder)*

---

## 📄 References

- Clementz et al. (2016). Identification of Distinct Psychosis Biotypes Using Brain-Based Biomarkers. *Am J Psychiatry*
- Friston et al. (2017). Dynamic Causal Modelling and the Canonical Microcircuit. *Brain Struct Funct*
- B-SNIP Consortium. [https://bsnip.org](https://bsnip.org)

---

## 📌 Notes

> ⚠️ Raw EEG data from the B-SNIP study is not included due to data sharing agreements.  
> ✅ All scripts assume anonymized preprocessed EEG and are structured to run in SPM12 under MATLAB.

---

## 👨‍💻 Author

**Haoming Liu (刘浩铭)**  
MRes Brain Sciences | University College London  
GitHub: [@HMLiu012](https://github.com/HMLiu012)  
Email: haoming.liu@email.com

---

> _"If the brain were so simple we could understand it, we would be so simple we couldn't."_  
> — Emerson M. Pugh
