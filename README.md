# Diabetes-Diagnosis-from-Patients-Symptoms

**ABSTRACT**

Diabetes is a metabolic disease affecting a multitude of people worldwide. Its incidence rates are increasing alarmingly every year. If untreated, diabetes-related complications in many vital organs of the body may turn fatal. Early detection of diabetes is very important for timely treatment which can stop the disease progressing to such complications. RR-interval signals known as heart rate variability (HRV) signals (derived from electrocardiogram (ECG) signals) can be effectively used for the non-invasive detection of diabetes. This research paper presents a methodology for classification of diabetic and normal HRV signals using deep learning architectures. We employ long short-term memory (LSTM), convolutional neural network (CNN) and its combinations for extracting complex temporal dynamic features of the input HRV data. These features are passed into support vector machine (SVM) for classification. We have obtained the performance improvement of 0.03% and 0.06% in CNN and CNN-LSTM architecture respectively compared to our earlier work without using SVM. The classification system proposed can help the clinicians to diagnose diabetes using ECG signals with a very high accuracy of 95.7%.

**CONCLUSION**

We have developed a diabetes prediction system with the help of patients' symptoms. We have used mean of the features to take care of the missing values. We have experimented with several classifiers and found that “Random Forest” works better for diabetes prediction. We have presented the results with performance metrics like Accuracy, Precision, Recall and F1 score. Moreover, we have tuned hyper parameters of random forest and achieved the best accuracy possible
