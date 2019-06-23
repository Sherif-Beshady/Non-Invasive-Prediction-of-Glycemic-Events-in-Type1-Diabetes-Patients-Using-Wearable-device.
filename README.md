# Non-Invasive Prediction of Glycemic Events in Type1 Diabetes Patients Using Wearable device.
![glucose](https://github.com/Sherif-Beshady/Non-Invasive-Prediction-of-Glycemic-Events-in-Type1-Diabetes-Patients-Using-Wearable-device./blob/master/Capstone_June19/Screen%20Shot%202019-06-11%20at%2011.42.22%20am.png)

### *Background*
Hypoglycaemia and Hyperglycaemia are common phenomena that affect patients with diabetes. Early detection and prediction improve quality of life and lead to the avoidance of serious complications. 
Continuous glucose monitoring (CGM) currently being used for detection of glucose level, but they have restrictions; also, they are not preferable with a lot of the patients. Therefore, I aimed to investigate whether a machine algorithm that adds information about the intricate dynamic/pattern of heart rate, acceleration and breath rate coming from a wearable device in real life situation could improve the accuracy of Hypoglycaemia/Hyperglycaemia detection.

### *Economic Impact*
“For type 1 diabetes, the total annual cost in Australia is __$570 million__, with the total average annual cost per person being __$4,669__. 
The average total annual cost is __$3,468__ for people without complications, however this can rise to __$16,698__ for people with complications.” 
Source : Diabetes - the silent pandemic and its impact on Australia
A research by Baker IDI Heart and Diabetes Institute in Partnership with Diabetes Australia 

This means with every __1%__ overall improvement due to better diabetes management we can save up to  __$5.7 million AUD__ annually!

### *Method*
I used D1NAMO dataset: A multi-modal dataset for research on non- invasive type 1 diabetes management
The main challenge was in signal pre-processing because this is real-life conditions data.
The objective was to predict if the patient goes through Hyperglycaemia or not within the next 5 minutes. To achieve that I used an iterative process to clean the data and feed it to a Random Forest model, get the results, and go back to data pre-processing and model improvement until model results were consistent to some extent across the majority of patients.

### *Results*
 the machine learning algorithm was able to predict Hyperglycaemia successfully with an average of 69% across data set diabetes patients and a lead time of 5 minutes.

### *Future work*
-	Pre-processing of heart rate signal coming from a wearable device in a real-life condition is a very complicated and time-consuming process but has an impact on model accuracy.
-	explore the impact of other factors like food and insulin which I didn't include in my set of features.

### *Helpful links*
1. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4764234/ 
2. https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005232
3. https://static.diabetesaustralia.com.au/s/fileassets/diabetes-australia/e7282521-472b-4313-b18e-be84c3d5d907.pdf
4. https://pypi.org/project/heartpy/
5. https://pypi.org/project/biosppy/

