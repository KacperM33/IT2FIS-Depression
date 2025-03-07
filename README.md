# 🧠 An Interval Type-2 Fuzzy Inference System for Depression Diagnosis

The projects aims to develop an **Interval Type-2 Fuzzy Inference System** for depression diagnosis, as potential tool to support mental health specialists.<br><br>
System contains five input variables:
- **PHQ-9 Score**
- **BDI Score**
- **GAD-7 Score**
- **Sleep Quality**
- **Social Interactions** <br>

And as output returns **Depression Level**.

### ‼️ Warning

**It should be emphasized, that the system is used only for initial assessment, and a detailed diagnosis can only be made by a qualified medical specialist.**

## 📚 About This Project

The project was completed as a final project within the subject called *Fuzzy Systems* during my engineering studies.

## 🧰 Development Tools

- Python 3.12.2
- [PyIT2FLS](https://pyit2fls.readthedocs.io/en/latest/#)
- [Google Colab](https://colab.research.google.com) (Jupyter Notebook)

## 📊 Results

As example, for inputs:
- **PHQ-9 Score: 10**
- **BDI Score: 7**
- **GAD-7 Score: 5**
- **Sleep Quality: 1**
- **Social Interactions: 2**

### Charts:<br>

The first chart shows which rules was activated:<br>
![image](https://github.com/user-attachments/assets/2be0bdbd-c28d-4167-b326-f1177ca3e552)
<br><br>
The second chart shows rules after aggregation:<br>
![image](https://github.com/user-attachments/assets/6c92d2dd-2ab3-466c-8e67-5e7541b29327)

And after defuzzyfication the output assigned rounded value of **32** which is equal to **Low Depression Level**.
