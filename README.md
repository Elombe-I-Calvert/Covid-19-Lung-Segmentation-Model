# Covid-19-Lung-Segmentation-Model

**A Web-based Application for the Prognostication of COVID-19 Patient Outcomes Through the Application of Machine Learning and Deep Learning Techniques on A Heterogeneous Dataset of CT-Chest Images &amp; Clinical Data**

<div align="justify"> 
  
**Introduction:** COVID-19 was named a pandemic on March 11, 2020, by the World Health Organization (WHO). Unfortunately, patients with COVID-19-associated acute-respiratory distress syndrome (ARDS) frequently require intubation and intensive care unit (ICU) care, both of which are costly and limited, especially within developing countries. Thus, knowing a patient's prognosis shortly after admission to the hospital can help with starting new medicines and therapies, resulting in better patient outcomes. This, although difficult, can be done reliably by applying computational approaches to the complex heterogeneous biomedical data obtained from COVID-19 hospitalized patients. With that said, this project aims to develop a clinical decision support system for physicians that will aid in the accurate determination of a COVID-19 patient’s prognosis at admission, whether they will die or recover, based on clinical, biological, and radiological data collected. 

**Methods:** For the categorization of CT chest images into categories of normal lung, no lung tissue, and lung tissue with pathology, a modified VGG-16 was utilized, with 13 layers. This model architecture was also used to classify the top 10 positive patients’ CT scans into recovered or deceased. A 12-layer multilayer perceptron was used to classify the structured data into recovered or deceased. The final prediction of a patient’s prognosis was done using a logistic regression model utilizing ridge regression. 

**Results:** The most successful outcome was delivered by the 13-layer CNN trained on CT images, obtaining an accuracy of 91 percent, as compared to using the structured data with an accuracy of 70 percent and a final prediction of 58 percent using logistic regression and L2 regularization. 

**Conclusion:** Complex, numerous biomedical data from covid-19 positive patients can be used to train models with accurately predict if a patient will recover or die from their infection. These models can be deployed as a web-based application for use by healthcare professionals. 

</div>
