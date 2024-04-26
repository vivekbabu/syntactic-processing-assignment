# syntactic-processing-assignment

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions. So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

The following is a snippet of medical data that may be generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done. “The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”

As we can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where we can understand the terms ‘cancer’ and ‘chemotherapy’.

Suppose we have been given such a data set in which a lot of text is written related to the medical domain. As we can see in the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which we saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence.

But, note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but somehow, we can build an algorithm to map the diseases and their respective treatment

Suppose we have been asked to determine the disease name and its probable treatment from the dataset and list it out in the form of a table or a dictionary like this.


Disease1     Treatment1, Treatment3, Treatment6
Disease2     Treatment2, Treatment4, Treatment7
Disease3     Treatment5, Treatment8, Treatment10


Our job is to build a custom NER to get the list of diseases and their treatment from the dataset.
