# 👩‍⚕️ Patient Survival Detection 🏥
#### _exploring **mlflow**, **Neural Networks**_ 
---
🧾Description: Getting a rapid understanding of the context of a patient’s overall health has been particularly important during the COVID-19 pandemic as healthcare workers around the world struggle with hospitals overloaded by patients in critical condition. Intensive Care Units (ICUs) often lack verified medical histories for incoming patients. A patient in distress or a patient who is brought in confused or unresponsive may not be able to provide information about chronic conditions such as heart disease, injuries, or diabetes. Medical records may take days to transfer, especially for a patient from another medical provider or system. Knowledge about chronic conditions can inform clinical decisions about patient care and ultimately improve patient survival outcomes.

🧭 Problem Statement: The target feature is hospital_death which is a binary variable. The task is to classify this variable based on the other 84 features step-by-step by going through each day's task. The scoring metric is Accuracy/Area under ROC curve.

---


## NEW Explorations: 
- **MLflow:** MLflow is an open-source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry.
- Did a few experiments with the Neural Network Architectures... and logged them in MLflow:<br>
  **Training set Plots:** <br>
  **Accuracy Graph of Multiple runs (experiments) >>** <br>
  ![accuracy](https://github.com/MaxxCode8/patient-survival-prediction/assets/105921273/60438e98-d467-4413-a3a9-f92532306c52) <br>
  **Loss >** <br>
  ![loss](https://github.com/MaxxCode8/patient-survival-prediction/assets/105921273/abe25a75-dcf9-49df-833c-083af31bab12)

### Need Much more Experimentation with mlflow... this is just an entry project into mlfow

#### Here's XAI Feature Impact aka summary plot:
  ![image](https://github.com/MaxxCode8/patient-survival-prediction/assets/105921273/e0fd52f8-6798-4880-a3af-584a384baf96)


---
## References:
### [MLFlow](https://mlflow.org/)

_Happy Learning!_ 🙏
