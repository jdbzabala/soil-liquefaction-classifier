
# SHIFTING SANDS - Soil Liquefaction Classifier
![Snip1](https://github.com/jdbzabala/soil-liquefaction-classifier/assets/143991175/7729a27e-4012-4565-a419-ff89aa1897d4)

In this project we utilized geotechnical data from sites monitored for soil liquefaction to create a model that would predict the susceptibility of a site from soil liquefaction.

## DATASET
The dataset used is from Idriss and Boulanger's conference paper on SPT Liquefaction Trigerring Procedures. Both the 2010 and 2014 release was used since their 2014 paper included corrections for the 2010 data.

https://faculty.engineering.ucdavis.edu/boulanger/wp-content/uploads/sites/71/2014/09/Idriss_Boulanger_SPT_Liquefaction_CGM-10-02.pdf

## MODEL
XGBoost Model with 84.69% accuracy

## Explainability
The project also involves explaining the model through DICE and Counterfactuals to explain the prediction.
![Explainability](https://github.com/jdbzabala/soil-liquefaction-classifier/assets/143991175/12c5cc22-2d6f-482b-9cee-7a8d7cc5a73c)


