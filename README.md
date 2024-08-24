# Digital Phenotype Profile: Data- driven tool to Evaluate Distress Experience in Healthcare Workers during COVID-19 Pandemic

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10258128/

# Abstract 
Background and objective:Due to the constraints of the COVID-19 pandemic, healthcare workers have reported acting in ways that are contrary to their moral values, and this may result in moral distress. This paper proposes the novel digital phenotype profile (DPP) tool, developed specifically to evaluate stress experiences within participants. The DPP tool was evaluated using the COVID-19 VR Healthcare Simulation of Stress Experience (HSSE) dataset (NCT05001542), which is composed of passive physiological signals and active mental health questionnaires. The DPP tool focuses on correlating electrocardiogram, respiration, photoplethysmography, and galvanic skin response with moral injury outcome scale (Brief MIOS).

Methods:Data-driven techniques are encompassed to develop a tool for robust evaluation of distress among participants. To accomplish this, we applied pre-processing techniques which involved normalization, data sanitation, segmentation, and windowing. During feature analysis, we extracted domain-specific features, followed by feature selection techniques to rank the importance of the feature set. Prior to classification, we employed 𝑘-means clustering to group the Brief MIOS scores to low, moderate, and high moral distress as the Brief MIOS lacks established severity cut-off scores. Support vector machine and decision tree models were used to create machine learning models to predict moral distress severities.

Results:Weighted support vector machine with leave-one-subject-out-cross-validation evaluated the separation of the Brief MIOS scores and achieved an average accuracy, precision, sensitivity, and F1 of 98.67%, 98.83%, 99.44%, and 99.13%, respectively. Various machine learning ablation tests were performed to support our results and further enhance the understanding of the predictive model.

Conclusion:Our findings demonstrate the feasibility to develop a DPP tool to predict distress experiences using a combination of mental health questionnaires and passive signals. The DPP tool is the first of its kind developed from the analysis of the HSSE dataset. Additional validation is needed for the DPP tool through replication in larger sample sizes.

# Tools and skills
- Digital phenotyping, COVID-19, Moral distress, VR, Data-driven
- Python, Machine learning, Clustering (supervised and unsupervised), Feature ranking (mRMR, LASSO, RELIEFF)
- Pandas, Numpy, SciKitLearn
