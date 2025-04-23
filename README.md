# 🧠 An Interval Type-2 Fuzzy Inference System for Depression Diagnosis

The project aims to develop an **Interval Type-2 Fuzzy Inference System** for **depression diagnosis** as a potential tool to support mental health specialists.<br><br>

### ‼️ Warning

**This system is intended for preliminary assessment only. A comprehensive diagnosis should always be conducted by a qualified medical specialist.**

## 📚 About This Project

This project was completed as the final assignment within for the *Fuzzy Systems* course during my engineering studies.

## 🧰 Development Tools

- Python 3.12.2
- [PyIT2FLS](https://pyit2fls.readthedocs.io/en/latest/#)
- [Google Colab](https://colab.research.google.com) (Jupyter Notebook)

## Project details

### 🔸 Inputs

The system takes five input variables related to mental health and lifestyle factors. These variables are commonly used in clinical assessments and provide valuable insights into a person's psychological state.

- **PHQ-9 Score**
<br>The **Patient Health Questionnaire-9** is a self-assessment tool for detecting depression severity.
<br>&nbsp;&nbsp;Range 0-27
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Low*: 0-10
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Medium*: 8-23
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *High*: 20-27

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/a3e130f2-0d4b-465e-bb83-6f44b6763201" width=500>


- **BDI Score**
<br>The **Beck Depression Inventory** evaluates emotional, cognitive, and physical symptoms of depression.
<br>&nbsp;&nbsp;Range: 0–63
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Low*: 0–13
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Medium*: 11–24
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Moderate*: 20–34
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *High*: 31–63

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/0bdc5bb5-0f09-4ba7-bbc1-7ea27f3d52ac" width=500>

- **GAD-7 Score**
<br>The **Generalized Anxiety Disorder-7** scale measures the severity of anxiety symptoms.
<br>&nbsp;&nbsp;Range: 0–21
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Low*: 0–7
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Medium*: 6–17
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *High*: 15–21

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/b59cbbcb-fcfd-4513-bcb2-7574872a6a43" width=500>

- **Sleep Quality** 
<br>A subjective rating of the individual’s overall sleep quality.
<br>&nbsp;&nbsp;Range: 1–5
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Very Poor*: 1–2
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Poor*: 1.5–3
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Moderate*: 2.5–4
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Good*: 3–4.5
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Very Good*: 4–5

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/4dbe7d94-5b60-42eb-a430-dfe2f6b85e66" width=500>

- **Social Interactions**
<br>A measure of how frequently and meaningfully the person engages in social activities.
<br>&nbsp;&nbsp;Range: 1–10
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Very Low*: 1–3
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Low*: 2–5
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Moderate*: 4–7
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *High*: 6–10

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/b9a1f271-bbcf-464b-90c0-e50d3de2c2a5" width=500>


### 🔸 Output 

As output, the system returns the **Depression Level**, classified into four fuzzy categories based on the interpreted input data.
<br>&nbsp;&nbsp;Range: 0–100
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Level 0 – No Depression*: 0–20
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Level 1 – Slight Depression*: 15–45
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Level 2 – Moderate Depression*: 40–70
<br>&nbsp;&nbsp;&nbsp;&nbsp;- *Level 3 – Severe Depression*: 65–100

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/35d7e89e-ab17-4dbd-9385-e5384f0bbe3d" width=500>


## 📊 Results

For example, given the following input values:
- **PHQ-9 Score: 10**
- **BDI Score: 7**
- **GAD-7 Score: 5**
- **Sleep Quality: 1**
- **Social Interactions: 2**

### Charts:<br>

- The first chart shows which rules was activated:<br>

![image](https://github.com/user-attachments/assets/2be0bdbd-c28d-4167-b326-f1177ca3e552)
<br><br>
- The second chart shows rules after aggregation:<br>

![image](https://github.com/user-attachments/assets/6c92d2dd-2ab3-466c-8e67-5e7541b29327)

After **defuzzification**, the system output a **rounded value of 32**, which corresponds to a **Low Depression Level**.
