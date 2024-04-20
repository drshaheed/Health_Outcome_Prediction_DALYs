# Healthcare Outcome Prediction for Inpatients

## Project Overview
This project aims to predict healthcare outcomes for inpatients based on their medical records. Specifically, we focus on predicting the Disability Adjusted Life Years (DALY) weightage, which is a measure of overall disease burden, expressed as the number of years lost due to ill-health, disability, or early death. The project uses machine learning techniques to analyze inpatient data and provide insights that could potentially help improve healthcare strategies and patient management.

## Dataset
The dataset used in this project is derived from the inpatient interview records and contains various attributes such as age, nationality, diagnosis, comorbidities, and DALY weightage. Due to privacy considerations, the data shared in this repository is synthetic and designed to mimic the structure and statistical properties of the original data.

## Features
The model considers the following features for predicting the DALY weightage:
- **Age**: The age of the patient.
- **Gender**: The gender of the patient.
- **Nationality**: The nationality of the patient.
- **Diagnosis**: The primary diagnosis.
- **Co-Morbidities**: Other medical conditions the patient has been diagnosed with.
- **Score Pre-intervention**: Clinical score before any intervention.
- **Score Post-Intervention**: Clinical score after the intervention.

## Models Used
The project employs a RandomForestRegressor for prediction due to its robustness and effectiveness in handling both non-linear relationships and interactions between features.


## Usage
The main notebook in this project contains detailed steps for data preprocessing, model training, evaluation, and visualization of results. You can run each cell in the notebook to reproduce the analysis and predictions.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Make sure to adjust the URLs and instructions based on how you manage your project repository and its details. If there's anything else you'd like to add or modify, let me know!
