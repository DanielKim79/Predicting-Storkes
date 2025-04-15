## Predicting Strokes

### Summary
A stroke is a serious physiological, medical event that occurs in the brain when the transport of blood is interrupted by either a blood vessel rupture or a blood clot. This disruption prevents brain cells from getting the oxygen they need and they begin to die within minutes. Strokes can have a number of physical and cognitive effects. Some examples include paralysis, difficulties swallowing, balance problems, vision problems, memory problems, aphasia, depression, and even death. In the United States, strokes are the 5th leading cause of death. And according to the World Health Organization, strokes are the 2nd leading cause of death globally.


### Rationale
By leveraging ML technology, we can develop models that can identify higher risk stroke patients.


### Research Question
Our goal in this exercise is to predict which factors can lead a patient getting a stroke. 


### Data Sources
We will be using the Stroke Prediction Dataset found on Kaggle.

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data


### Description of Files
'healthcare-dataset-stroke-data.csv' - Contains 10 features for predicting strokes.

'Predicting Strokes.ipynb' - this file contains the code that compares the different classifying models.


### Methodology
Compare different models for their accuracy, f1, recall, and precision to determine which is the best.

Identify which features are most important in determing a future stroke.


### Takeaways
The model that performs the best is Gradient Boosting.

This model performs extremely well in predicting strokes, with an accuracy of 95%, a precision score of 99%, a recall score of 91%, and an F1-score of 0.95.

The features of most importance are Average Gluocose Level and Age.


### Conclusion
We can use this model to flag and inform higher risk patients and have their doctor make recommendations.

We can also make dietary and lifestyle recommendations to younger patients with higher Average Glucose Levels as preventive measure. 


### Future Improvements
Track patients over time and calculate the true accuracy of our model.

Make adjustments to the model as new data is collected.
