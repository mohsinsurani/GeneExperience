Cancer Classification by Gene Expression Monitoring
This dataset is derived from the landmark proof-of-concept study published by Golub et al. in 1999, titled "Molecular Classification of Cancer: Class Discovery and Class Prediction by Gene Expression Monitoring". The study demonstrated a novel approach to classifying new cases of cancer through gene expression monitoring using DNA microarray technology. This methodology has since become a foundational technique in identifying new cancer classes and assigning tumors to known classes based on their gene expression profiles.

Study Overview
The study focused on distinguishing two types of leukemia:

Acute Myeloid Leukemia (AML)
Acute Lymphoblastic Leukemia (ALL)
Gene expression data from DNA microarrays were used to classify patient samples into these two categories. By monitoring the expression levels of thousands of genes, the researchers were able to develop models for cancer classification and prognosis, providing critical insights into the molecular underpinnings of these cancers.

Datasets
This repository contains two datasets used in the original study:

Training Dataset (38 samples)

This dataset was used to build the initial classification model. It contains gene expression measurements from both AML and ALL samples, sourced from Bone Marrow and Peripheral Blood.
Test Dataset (34 samples)

This dataset was independently tested against the trained model to evaluate its predictive accuracy. Like the training set, it includes gene expression data from AML and ALL patients.
Key Details:
The intensity values in both datasets have been re-scaled so that the overall intensities for each chip are equivalent, ensuring that the results are comparable across different samples.
The datasets can be used for tasks such as:
Gene expression analysis
Cancer classification
Predictive model development
Comparative studies on leukemia types (AML vs. ALL)


Reference:
Golub et al
"Molecular Classification of Cancer: Class Discovery and Class Prediction by Gene Expression Monitoring"
Science, 1999, 286(5439), 531-537.
