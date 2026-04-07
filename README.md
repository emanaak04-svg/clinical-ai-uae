# Clinical AI — UAE Patient Risk Screening

> AI-powered clinical risk assessment engine designed for UAE hospital workflows.  
> Built to address the high prevalence of Type 2 Diabetes and Hypertension across Abu Dhabi and Al Ain healthcare facilities.

---

## Overview

This project is the foundational engine of a bilingual clinical AI assistant targeting UAE hospitals.
The system analyzes patient-reported symptoms and flags risk levels for chronic diseases —
the leading cause of mortality in the UAE, where 1 in 5 adults has diabetes.

The long-term goal is to support physicians with AI-assisted documentation and early risk detection,
reducing administrative burden and enabling faster clinical decisions.

---

## Current Capabilities

- Symptom-based risk assessment for Type 2 Diabetes and Hypertension
- Multi-patient batch screening with structured report output
- Risk stratification: HIGH / MODERATE / LOW with matched clinical indicators
- Automated summary flagging patients requiring immediate follow-up

---

## Clinical Context

The UAE faces one of the highest chronic disease burdens globally:

- **12.3%** adult diabetes prevalence (IDF, 2023)
- **Cardiovascular disease** accounts for 34% of all non-communicable disease deaths
- Abu Dhabi's Department of Health serves **2,000+ connected facilities** via the Malaffi health exchange

This tool is designed with these realities in mind — built for the UAE, not adapted from elsewhere.

---

## Project Structure

clinical-ai-uae/
├── risk_engine.py      # Core risk assessment and report generation
└── README.md           # Project documentation
---

## Sample Output

CLINICAL AI — UAE PATIENT RISK SCREENING
Conditions: Type 2 Diabetes | Hypertension
Patient ID : UAE-003
Name       : Khalid Al Rashidi
Age        : 61  |  Gender: Male
Symptoms   : excessive thirst, fatigue, blurry vision, severe headache, chest pain

⚑ Diabetes        Risk: HIGH

Indicators : excessive thirst, fatigue, blurry vision

⚑ Hypertension    Risk: HIGH

Indicators : fatigue, blurry vision, severe headache, chest pain
---

## Roadmap

- [x] Rule-based symptom risk engine
- [ ] OpenAI API integration — conversation to clinical note
- [ ] Arabic language support (bilingual input)
- [ ] Web interface for clinical demo
- [ ] Validation with UAE-based medical professionals

---

## Author

**Eman Ayman AbuKhousa**  
BSc Data Science & AI — IIT Guwahati  
Building toward a clinical AI startup for Abu Dhabi hospitals  

---

## Disclaimer

This tool is a research prototype and is not intended for clinical use.
All patient data used in development is synthetic.
