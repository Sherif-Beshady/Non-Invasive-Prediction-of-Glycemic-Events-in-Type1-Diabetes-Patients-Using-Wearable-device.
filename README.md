# Non-Invasive Prediction of Glycemic Events in Type1 Diabetes Patients Using Wearable device.

### *Background*
Hypoglycaemia and Hyperglycaemia are common phenomena that affect patients with diabetes. Early detection and prediction improve quality of life and lead to the avoidance of serious complications. 
Continuous glucose monitoring (CGM) currently being used for detection of glucose level, but they have restrictions; also, they are not preferable with a lot of the patients. Therefore, I aimed to investigate whether a machine algorithm that adds information about the intricate dynamic/pattern of heart rate, acceleration and breath rate coming from a wearable device in real life situation could improve the accuracy of Hypoglycaemia/Hyperglycaemia detection.

### *Method*
I used D1NAMO dataset: A multi-modal dataset for research on non- invasive type 1 diabetes management
The main challenge was in signal pre-processing because this is real-life conditions data.
The objective was to predict if the patient goes through Hyperglycaemia or not within the next 5 minutes. To achieve that I used an iterative process to clean the data and feed it to a Random Forest model, get the results, and go back to data pre-processing and model improvement until model results were consistent to some extent across the majority of patients.

### *Results*
 the machine learning algorithm was able to predict Hyperglycaemia successfully with an average of 69% across data set diabetes patients and a lead time of 5 minutes.

### *Future work*
-	Pre-processing of heart rate signal coming from a wearable device in a real-life condition is a very complicated and time-consuming process but has an impact on model accuracy.
-	explore the impact of other factors like food and insulin which I didn't include in my set of features.   
