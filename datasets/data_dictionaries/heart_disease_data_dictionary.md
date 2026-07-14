# The UCI Heart Disease Dataset

The **UCI Heart Disease Dataset** contains demographic information, clinical measurements, and diagnostic test results collected from patients undergoing evaluation for heart disease.

Originally developed by the Cleveland Clinic Foundation and made available through the **UCI Machine Learning Repository**, this dataset has become one of the most widely used medical datasets for teaching statistics, data science, and machine learning.

The dataset contains **303 patient records** and **14 variables**, including patient demographics, results from diagnostic tests, and a diagnosis indicating the presence and severity of heart disease.

The original target variable records heart disease severity on a scale from **0 (no heart disease)** to **4 (most severe heart disease)**. Depending on the application, this variable is sometimes converted into a binary outcome indicating whether heart disease is present.

The dataset is suitable for learning:

- Data exploration
- Data visualization
- Data wrangling
- Statistical analysis
- Classification
- Machine learning

---

# Variables

## Age

- **Variable:** `age`
- **Type:** Numerical

Age of the patient measured in years.

---

## Sex

- **Variable:** `sex`
- **Type:** Binary Categorical

Biological sex of the patient.

Possible values:

- **0** = Female
- **1** = Male

---

## Chest Pain

- **Variable:** `chest_pain`
- **Type:** Nominal Categorical

Type of chest pain experienced by the patient.

Possible values:

- **1** = Typical Angina
- **2** = Atypical Angina
- **3** = Non-anginal Pain
- **4** = Asymptomatic

---

## Resting Blood Pressure

- **Variable:** `resting_bp`
- **Type:** Numerical

Resting blood pressure measured in **millimeters of mercury (mm Hg)**.

---

## Cholesterol

- **Variable:** `cholesterol`
- **Type:** Numerical

Serum cholesterol level measured in **milligrams per deciliter (mg/dL)**.

---

## High Blood Sugar

- **Variable:** `high_blood_sugar`
- **Type:** Binary Categorical

Indicates whether the patient's fasting blood sugar exceeds **120 mg/dL**.

Possible values:

- **0** = False (≤ 120 mg/dL)
- **1** = True (> 120 mg/dL)

---

## Resting ECG

- **Variable:** `resting_ecg`
- **Type:** Nominal Categorical

Results of the resting electrocardiogram (ECG).

Possible values:

- **0** = Normal
- **1** = ST-T Wave Abnormality
- **2** = Left Ventricular Hypertrophy

---

## Maximum Heart Rate

- **Variable:** `max_heart_rate`
- **Type:** Numerical

Maximum heart rate achieved during exercise.

---

## Exercise-Induced Angina

- **Variable:** `exercise_angina`
- **Type:** Binary Categorical

Indicates whether the patient experienced angina (chest pain) during exercise.

Possible values:

- **0** = No
- **1** = Yes

---

## ST Depression

- **Variable:** `st_depression`
- **Type:** Numerical

Amount of ST segment depression induced by exercise relative to rest.

Higher values generally indicate a greater degree of abnormality during exercise testing.

---

## ST Slope

- **Variable:** `st_slope`
- **Type:** Ordinal Categorical

Slope of the ST segment during peak exercise.

Possible values:

- **1** = Upsloping
- **2** = Flat
- **3** = Downsloping

---

## Major Vessels

- **Variable:** `major_vessels`
- **Type:** Numerical (Discrete)

Number of major blood vessels (0–3) colored by fluoroscopy.

Larger values indicate that more major vessels were visible during imaging.

---

## Thallium Stress Test

- **Variable:** `thal_test`
- **Type:** Nominal Categorical

Result of the thallium stress test.

Possible values:

- **3** = Normal
- **6** = Fixed Defect
- **7** = Reversible Defect

---

## Heart Disease

- **Variable:** `heart_disease`
- **Type:** Ordinal Categorical (Target)

Diagnosis of heart disease.

Possible values:

- **0** = No heart disease
- **1** = Mild heart disease
- **2** = Moderate heart disease
- **3** = Severe heart disease
- **4** = Very severe heart disease

Larger values indicate increasing severity of diagnosed heart disease.
