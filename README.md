# Cysteine pK<sub>a</sub> Benchmark Set

This repository contains the input structures and parameter files used for our cysteine pK<sub>a</sub> benchmark study. The dataset is designed to evaluate *in silico* tools for predicting cysteine pK<sub>a</sub> values and consists of **16 wildtype** and **10 mutant** proteins. All experimentally measured cysteine pK<sub>a</sub> values serving as the ground truth for this dataset were curated from the [PKAD database](http://compbio.clemson.edu/lab/software/5/).

## 📁 Repository Structure

The directory is organized into the following folders based on file types and subsets:

* **`wildtype-set_pdb-files/`** Contains the starting PDB (Protein Data Bank) structural files for the 16 wildtype proteins analyzed in the benchmark study.

* **`mutant-set_pdb-files/`** Contains the PDB structural files for the 10 mutant proteins used in the dataset evaluation.

* **`Amber-MD_inputs/`** Includes input files and necessary parameters for running Amber Molecular Dynamics (MD) simulations, specifically containing the modified thiolate Cysteine parameters utilized in the study's methodology.

## 📝 Citation

If you use this dataset or find our work helpful in your research, please cite the original benchmark study:

> **Awoonor-Williams, E., *et al.*** Benchmarking *in silico* Tools for Cysteine pK<sub>a</sub> Prediction. *Journal of Chemical Information and Modeling (JCIM)*, **2023**, 63(7), 2170-2180.  
> **DOI:** [10.1021/acs.jcim.3c00004](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00004)

---
*For complete methodology details and benchmark results, please refer to the main publication.*
