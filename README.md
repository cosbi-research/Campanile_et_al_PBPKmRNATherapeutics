# Code Associated with the Paper

**E. Campanile, E. Pettinà, S. Giampiccolo, L. Leonardelli, and L. Marchetti**  
*Physiologically Based Pharmacokinetic Modeling of mRNA-Encoded Therapeutics:  
A Multiscale Framework Integrating LNP and Antibody Trafficking in Mice*

---

## Software

The code was developed using **MATLAB SimBiology (version 2025b)**.

---

## Repository Overview

This repository contains the SimBiology project used to reproduce the simulations
of multiple mRNA-encoded therapeutics described in the main text and in the
**Supplemental Materials** of the manuscript.

---

## Models Included

The project includes **six models**:

- **Five models** corresponding to individual mRNA-encoded antibody therapeutics  
- **One model** used for simulations of recombinant proteins of different sizes,  
  as described in the Supplemental Materials

All models share the same underlying structure and differ only in:
- mRNA chain length  
- Therapeutic-specific parameters  
- Administered doses  
- Model variants  

Each model also includes a variant corresponding to the **“no-chain” case**, as
described in the main text and Supplemental Materials.

---

## Simulations

The **Model Analyzer** contains six simulation programs, one for each model.
These simulations differ only in their:
- Initial conditions  
- Simulated time spans  
