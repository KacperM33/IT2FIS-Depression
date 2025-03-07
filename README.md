# 🧠 An Interval Type-2 Fuzzy Inference System for Depression Diagnosis

The project aims to develop an **Interval Type-2 Fuzzy Inference System** for **depression diagnosis** as a potential tool to support mental health specialists.<br><br>
The system takes five input variables:
- **PHQ-9 Score**
- **BDI Score**
- **GAD-7 Score**
- **Sleep Quality**
- **Social Interactions** <br>

As output, it returns the **Depression Level**.

### ‼️ Warning

**This system is intended for preliminary assessment only. A comprehensive diagnosis should always be conducted by a qualified medical specialist.**

## 📚 About This Project

This project was completed as the final assignment within for the *Fuzzy Systems* course during my engineering studies.

## 🧰 Development Tools

- Python 3.12.2
- [PyIT2FLS](https://pyit2fls.readthedocs.io/en/latest/#)
- [Google Colab](https://colab.research.google.com) (Jupyter Notebook)

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
