# App Usage Analyzer (with Privacy Insights)

This is a mini project developed using *Python* and *Jupyter Notebook*, aimed at analyzing mobile app usage data and identifying potential privacy risks based on app permissions.

---

##  Project Objective

To simulate mobile app usage data, analyze how much time is spent on each app, categorize apps by type (social, productivity, etc.), and assess their privacy risk based on the number of permissions they request.

---

## Tools & Libraries Used

- pandas – for data handling and analysis  
- matplotlib – for basic data visualization  
- plotly – for interactive graphs  
- random – to generate realistic sample data  

---

## Features

- Generates realistic sample data for 10 common apps
- Analyzes time spent on each app
- Groups apps by category (Social, Productivity, Entertainment, etc.)
- Assigns a *Privacy Risk Level* based on:
  - Number of permissions used
  - Time spent on the app
- Visualizes insights using:
  - Bar chart (App usage time)
  - Pie chart (Category breakdown)
  - Scatter plot (Privacy vs Usage)

---

## Privacy Risk Scoring

A rule-based scoring system is applied:
- *High Risk: ≥4 permissions* *and* >200 minutes usage  
- *Medium Risk*: ≥3 permissions  
- *Low Risk*: <3 permissions  

This helps highlight apps that are both overused and invasive.

---

##  File Info

- screentimeapp.ipynb – Main notebook with code, visualizations, and insights

---

##  Screenshots

![WhatsApp Image 2025-07-30 at 17 25 37_b8bd0336](https://github.com/user-attachments/assets/d6bb76cc-1917-4445-b88f-dc2c82528a1f)
![WhatsApp Image 2025-07-30 at 17 31 19_f8aed93a](https://github.com/user-attachments/assets/66c61f76-1c0c-4d71-8156-105129212566)
![WhatsApp Image 2025-07-30 at 17 31 44_e0eb2d6c](https://github.com/user-attachments/assets/b17a5bfa-579d-451f-9d9b-1a1ca844cee7)

---

---

## Mini Project by
## Chandhna A & Harish P K (Team-3)
