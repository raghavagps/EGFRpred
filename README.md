# EGFRpred: QSAR based model for discriminating EGFR inhibitors and non-inhibitors using Random forest

**EGFRpred** is a computational platform designed for the identification and classification of inhibitors and non-inhibitors of the **Epidermal Growth Factor Receptor (EGFR)**.
While previous QSAR (Quantitative Structure-Activity Relationship) models were often limited to specific chemical classes like quinazoline derivatives, this resource was developed using a large and diverse dataset of approximately **3,500 molecules** to provide broader predictive power.

**Web Server:** https://webs.iiitd.edu.in/oscadd/egfrpred/index.php


## Citation

Singh, H., Singh, S., Singla, D., Agarwal, S. M., & Raghava, G. P. S. (2015).
**QSAR based model for discriminating EGFR inhibitors and non-inhibitors using Random forest.** *Biology Direct*, 10, 10.
[https://doi.org/10.1186/s13062-015-0046-9](https://www.google.com/search?q=https://doi.org/10.1186/s13062-015-0046-9)


## About the Research

EGFR is a well-characterized drug target for various cancers, including lung and breast cancer. This resource addresses the need for a robust classification model capable of handling diverse chemical scaffolds.

* **Diverse Dataset:** The model was trained, tested, and validated on a dataset of ~3,500 molecules, including scaffolds such as quinazolines, pyrimidines, quinolines, and indoles.


* **Threshold Definition:** Molecules are classified based on a strict inhibition activity threshold ($IC_{50}$ less than 10 nM for inhibitors).



## Key Features

### 1. High-Performance Classification

* **Machine Learning:** Utilizes a **Random Forest**-based model which achieved a maximum accuracy of **83.7%** and a Matthews Correlation Coefficient (MCC) of 0.49 on a validation set.


* **Molecular Fingerprints:** Prediction is based on **881 PubChem fingerprints**, which capture the structural and chemical features of the molecules.



### 2. Feature Selection & Analysis

* **Top Fingerprints:** The study identified specific chemical features (fingerprints) most associated with EGFR inhibition, such as **FP380** (C(~O)(~O)) and **FP579** (O=C-C-C-C).


* **Validation:** The models were rigorously evaluated on an independent dataset to ensure reliability across different chemical spaces.



### 3. Integrated Web Services

* **Predictive Tool:** Users can submit chemical structures to predict whether they are likely to be potent EGFR inhibitors ($IC_{50} < 10$ nM).


* **Data Exploration:** Facilitates the identification of structural motifs essential for binding to the EGFR kinase domain.



## Applications

* **Virtual Screening:** Efficiently screening large chemical libraries to identify potential new EGFR inhibitors.


* **Drug Design:** Assisting medicinal chemists in optimizing leads by identifying critical molecular fingerprints.


* **Chemo-informatics:** Providing a robust benchmark and dataset for the development of new QSAR methodologies.



## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

IIIT Delhi

## Support

The development of EGFRpred was supported by the **Council of Scientific and Industrial Research (CSIR)** and the **Department of Biotechnology (DBT)**, Government of India.
