Predicting Antipsychotic Responsiveness in Schizophrenia Using Machine Learning
This repository contains the code used in the study titled "Predicting Antipsychotic Responsiveness Using a Machine Learning Classifier Trained on Plasma Levels of Inflammatory Markers in Schizophrenia". The code is structured to facilitate feature selection, model building, and explainable AI analysis to predict pharmacological subtypes within schizophrenia, including antipsychotic response, clozapine response, and schizophrenia status.

Authors
Jie Yin Yee<sup>1</sup>
Ser-Xian Phua<sup>2</sup> (GitHub Maintainer)
Email: phuasx@gmail.com
Yuen Mei See<sup>1</sup>
Anand Kumar Andiappan<sup>3</sup>
Wilson Wen Bin Goh<sup>2,43,54,65,76</sup>
Jimmy Lee<sup>1,2</sup>
Affiliations:

<sup>1</sup> North Region, Institute of Mental Health, Singapore
<sup>2</sup> Lee Kong Chian School of Medicine, Nanyang Technological University, Singapore
<sup>3</sup> Singapore Immunology Network (SIgN), Agency for Science, Technology and Research (A*STAR), Singapore
<sup>34</sup> Center for Biomedical Informatics, Nanyang Technological University, Singapore
<sup>45</sup> School of Biological Sciences, Nanyang Technological University, Singapore
<sup>56</sup> Center of AI in Medicine, Nanyang Technological University, Singapore
<sup>67</sup> Division of Neurology, Department of Brain Sciences, Faculty of Medicine, Imperial College London

Repository Structure
This repository contains three main Python scripts:

Feature Selection (SVM RFE workflow)
feature_selection_olink.py
This script implements Support Vector Machine Recursive Feature Elimination (SVM-RFE) for feature selection. It helps identify the most important inflammatory markers contributing to antipsychotic responsiveness in schizophrenia.

Prediction Modeling
modelling_olink.py
This script builds the prediction models using the selected features. Various machine learning classifiers are trained and evaluated for their ability to predict pharmacological subtypes, including antipsychotic and clozapine response.

Explainable AI (SHAP analysis)
shap_xai_olink.py
This script uses SHAP (SHapley Additive exPlanations) to provide explainable insights into the prediction models. SHAP helps visualize the contribution of each feature to the model’s predictions, enhancing interpretability.

Requirements
To run the code, you will need the following Python libraries:

numpy
pandas
scikit-learn
matplotlib
seaborn
shap
You can install the required packages by running:

bash
Copy code
pip install -r requirements.txt
Usage
Each script can be executed independently. Ensure that the input data (plasma levels of inflammatory markers) is correctly formatted as expected by the scripts. Modify the paths and any configuration settings as needed.

Example usage:

bash
Copy code
python feature_selection_olink.py
python modelling_olink.py
python shap_xai_olink.py
Availability
The code is currently available upon request. Please contact the repository maintainer, Ser-Xian Phua (phuasx@gmail.com), for access.

Citation
If you use this code in your research, please cite the related manuscript:

"Predicting Antipsychotic Responsiveness Using a Machine Learning Classifier Trained on Plasma Levels of Inflammatory Markers in Schizophrenia"

