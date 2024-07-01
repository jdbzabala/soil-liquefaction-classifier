
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
![Explainability](https://github.com/jdbzabala/soil-liquefaction-classifier/assets/143991175/3ea48bc3-5a76-4a85-880b-8e2f426fd3dd)

![Explain2](https://github.com/jdbzabala/soil-liquefaction-classifier/assets/143991175/b85463ff-a940-403c-9e12-e24f8753ca96)

