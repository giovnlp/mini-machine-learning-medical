# 🧮 SIRS Calculator

This is a simple Python script that calculates a SIRS (Systemic Inflammatory Response Syndrome) score based on patient vital signs.

## 📋 What is SIRS?

SIRS is a clinical response to a nonspecific insult, including infection, trauma, pancreatitis, ischemia, etc. A patient is considered to meet the SIRS criteria if they have **2 or more** of the following:

- Temperature > 37.5°C or < 36.5°C  
- Respiratory Rate > 20 breaths/min or PaCO₂ < 32 mmHg  
- Heart Rate > 90 bpm  
- White blood cell count > 12 or < 4 (x10⁹/L)

## 🩺 How it works

The script interacts with the user through the terminal, asking for:

- Body temperature  
- Respiratory rate  
- PaCO₂ level  
- Heart rate  
- White blood cell count

Each input is validated. If a value meets any SIRS criteria, it adds one point to the total score. At the end, the total SIRS score is printed and a final message tells whether the patient meets the SIRS condition.

--> This mini project was made based on an online artifical inteligence medical course.
