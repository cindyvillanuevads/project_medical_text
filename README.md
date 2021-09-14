# Medical transcripts Project

## PROJECT DESCRIPTION
-  Medical data is extremely hard to find due to HIPAA privacy regulations. This data was scraped from mtsamples.com
and  contains sample medical transcriptions for various medical specialties.



## GOALS 


- Predict the medical specialties based on the transcription text  using property data that was  scraped from mtsamples.com.





### DATA DICTIONARY

| Feature | Definition | Data Type |
| --- | ---------------- | -------|
|description| chief complain | object |
|transciption| medical record for the visit|object|
|sample_name| transciption title| object|
|keywords| relevant keywords form transcriptions|object|






| Target | Definition | Data Type |
| --- | --- | -------|
|medical_specialty|medical specialty classification of transcription|object|








## PROJECT PLANNIG



### Acquire
- Acquire data from [Kaggle](https://www.kaggle.com/tboyle10/medicaltranscriptions) 
### Prepare
- Clean and prepare data for preparation step. 
Split dataset into train, validate, test. Separate target from features and scale the selected features. Create a function to automate the process. The function is saved in a prepare.py module. 
### Explore
- Visualize all combinations of variables.Define two hypotheses, set an alpha, run the statistical tests needed, document findings and takeaways.
### Model
- Extablishing and evaluating a baseline model.
- Document various algorithms and/or hyperparameters you tried along with the evaluation code and results.
- Evaluate the  models using the standard techniques: computing the evaluation metrics 
- Choose the model that performs the best.
- Evaluate the best model (only one) on the test dataset.




## INITIAL IDEAS/ HYPOTHESES STATED
- 𝐻𝑜 :
- 𝐻𝑎 : 

## INSTRUCTIONS FOR RECREATING PROJECT

- [x] Read this README.md
- 
- [ ] Download the  prepare.py, explore.py , model.py,  evaluate.pyand  and ___  into your working directory
- [ ] Run the ___ notebook


## DELIVER:
- A github repository containing my work.
- README file contains project description and goals, data dictionary, project planning, initial ideas/hypotheses, instructions to recreate project.

- Individual modules, .py files, that hold your functions to acquire and prepare your data.
