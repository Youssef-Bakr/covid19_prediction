# COVID-19 Prediction
Kaggle: [COVID19/SARS B-cell Epitope Prediction](https://www.kaggle.com/futurecorporation/epitope-prediction)

## Task 1 : SARS prediction with B-cell data
Estimating the epitope region of SARS-CoV by only analyzing the B-cell dataset.

* **Epitope**: Epitopes or *antigenic determinants* are regions of proteins that can trigger a cellular immune response mediated by T or B cells. T cell epitopes are usually protein antigen-derived peptides presented by MHC molecules on antigen-presenting cells and recognized by T-cell receptors.
* **B-cell**: B-cells fight bacteria and viruses by making Y-shaped proteins called *antibodies*, which are specific to each pathogen and are able to lock onto the surface of an invading cell and mark it for destruction by other immune cells.

### Task Details
Classifying peptides into two categories: 
* antibodies with inducing properties (positive)
* antibodies without inducing properties (negative)

Develop a model to predict the antibody valence of the SARS-CoV data.

### Evaluation
* Area Under the Curve(AUC)
  * AUC of epitope prediction for SARS using the B-cell dataset as the training set and the SARS dataset as the test set.
