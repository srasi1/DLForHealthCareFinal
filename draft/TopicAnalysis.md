## Learning from Claims Data
mentor: [Rick Barber](mailto:barber5@illinois.edu)

#### Description
Claims data are structured data representing all of the insurance claims for a given set of patients over a period of time. 
The data are less rich than EHR data but in general more complete, spanning potentially many different care venues. 
Claims data are used to predict cost and utilization for individuals or cohorts of patients. 
They are also used to develop risk stratification (classification) models. 

#### Tasks
1. choose a disease or procedure to do risk modeling on
2. build a model for utilization prediction (patient cost prediction) or payer response prediction

##### Question:


#### Dataset: 
 - You are free to use any public dataset.
 - IQVIA PharMetrics Plus Dataset [Barber, Richard](mailto:barber5@illinois.edu) for access)

#### Related work and references:
 - ***Combining an embedding with a multitask learning network in order to predict what payers will approve or decline to cover claims***
    (Deep claim: Payer response prediction from claims data with deep learning. arXiv preprintarXiv:2007.06229, 2020.)
 - Use an existing network called SkimGram to model and predict the risk of hospitalization for pediatric patients
    (A deep learning model for pediatric patient risk stratification. Am J Manag Care, 25(10):e310–e315, 2019)
 - Explore risk modeling of total joint replacement procedure and adverse events that could occur afterwards. They compare implementations with random forests, CNNs, and RNNs in their study.
    (Predictive modeling of the total joint replacement surgery risk: a deep learning based approach with claims data. AMIA Summits on Translational Science Proceedings, 2019:562, 2019)
 - ***Risk prediction of readmission to hospital for COPD patients. They do a good job reviewing some of the issues associated with the temporality of claims data. They also explore a potential attention mechanism for the task.***
    (Predictive modeling of the hospital readmission risk from patients’ claims data using machine learning: a case study on copd. Scientific reports, 9(1):1–10, 2019.)
 - ***Built a deep neural network for cost/utilization prediction. They did an analysis afterwards of which procedure and diagnosis codes were most important for predicting cost and utilization at a population level***   
    (Deep learning for prediction of population health costs. arXiv preprint arXiv:2003.03466, 2020.)
 - Writeup on a survey on some of the challenges and opportunities associated with using claims data. 
        This might be a good paper to look at for brainstorming project ideas.
    (Combining the power of artificial intelligence with the richness of healthcare claims data: opportunities and challenges. PharmacoEconomics, 37(6):745–752, 2019.)
