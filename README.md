# TumorHoPe2: An updated database for Tumor Homing Peptides

Welcome to the official repository and documentation overview for **TumorHoPe2**, an extensively updated and enhanced version of the original TumorHoPe database. This resource serves as a comprehensive platform for the study of **Tumor Homing Peptides (THPs)**—short amino acid sequences that specifically recognize and bind to tumor cells or their vascular microenvironment.

**Web Server:** [https://webs.iiitd.edu.in/raghava/tumorhope2/](https://webs.iiitd.edu.in/raghava/tumorhope2/)



## Citation

Kashyap, D., Gupta, D., Mehta, N. K., & Raghava, G. P. S. (2025). 
**TumorHoPe2: An updated database for Tumor Homing Peptides.** *Preprint/Manuscript.* [https://doi.org/10.48550/arXiv.2505.20913](https://doi.org/10.48550/arXiv.2505.20913)


The dataset can be also found on Zenodo (**https://doi.org/10.5281/zenodo.20072410**)




## About the Database

**TumorHoPe2** was developed to provide a significantly expanded and more detailed resource compared to its predecessor. It catalogs experimentally validated peptides that home into tumor tissues through the circulatory system, facilitating the development of targeted cancer therapeutics, diagnostics, and theranostics.

The updated database integrates data from:
* **Expanded Literature Search:** Exhaustive curation of studies published between 2011 and 2024.
* **Validated Experiments:** Data from *in vivo* (e.g., phage display, biodistribution) and *in vitro* (e.g., cell binding, internalization) assays.
* **Diverse Biological Sources:** Peptides targeting various tumor types, cell lines, and specific receptors.



## Key Features

### Comprehensive Dataset
* **1,617 unique peptides:** Over 2.5x the size of the original database (increased from 744 to 1,617).
* **Target Diversity:** Covers over 50 different types of tumors and 150+ cancer cell lines.
* **Detailed Annotations:** Includes sequence, target organ, cell line, experimental method, and reported receptors (e.g., integrins, nucleolin).

### Built-in Tools
* **Similarity Search:** Integrated **BLAST** and **Smith-Waterman** algorithms for identifying homologous homing peptides.
* **Peptide Mapping:** Tool to map known THPs onto user-defined protein sequences to identify potential homing motifs.
* **Advanced Search:** Multi-criteria filtering by peptide length, target tumor, cell line, and experimental validation type.



## Overview

TumorHoPe2 is organized to provide high-quality data and advanced visualization:
1.  **Primary Data:** Manually curated experimental evidence including peptide sequence, validation assay, and target specificity.
2.  **Structural Data:** 3D structures predicted using **AlphaFold2/PEPstr** and secondary structure information.
3.  **Physicochemical Analysis:** Calculations for hydrophobicity, hydrophilicity, molecular weight, isoelectric point (pI), and formal charge.
4.  **Interactive Visualization:** Integration with **NGL Viewer** for real-time 3D exploration of peptide structures.



## Applications

* **Targeted Drug Delivery:** Designing peptide-drug conjugates (PDCs) and nanocarriers for localized cancer treatment.
* **Diagnostic Imaging:** Engineering molecular probes for tumor-specific PET, MRI, or fluorescent imaging.
* **Bioinformatics Research:** Utilizing the dataset to train machine learning models for the prediction of novel tumor homing peptides.



## Contact & Authors

**Prof. G.P.S. Raghava**
[raghava@iiitd.ac.in](mailto:raghava@iiitd.ac.in)
Department of Computational Biology,
Indraprastha Institute of Information Technology (IIIT Delhi),
Okhla Phase III, New Delhi-110020, India.



## License

This database is distributed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**, which permits unrestricted use, distribution, and reproduction in any medium, provided the original work is properly cited.
