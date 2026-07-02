# 🩺 Case 001 – Acute Chest Pain in a High-Risk Adult

---

# Metadata

| Field | Value |
|-------|-------|
| Case ID | PCRD-001 |
| Specialty | Emergency Medicine |
| Clinical Domain | Cardiology |
| Difficulty | 🔴 Advanced |
| Educational Level | Medical Students, Residents, Physicians |
| Estimated Time | 15–20 minutes |
| Primary Diagnosis | ST-Elevation Myocardial Infarction (STEMI) |
| Version | 1.0 |

---

# Project Objective

This case is designed to demonstrate physician-level clinical reasoning while providing a structured benchmark for Healthcare Artificial Intelligence (Healthcare AI) evaluation.

The objective is not only to reach the correct diagnosis, but to demonstrate safe, transparent, evidence-based reasoning throughout the clinical decision-making process.

---

# Clinical Scenario

A 39-year-old man presents to the Emergency Department complaining of severe central chest pain that started one hour ago while resting.

He describes the pain as heavy, pressure-like, and radiating to his left shoulder.

Associated symptoms include:

- Diaphoresis
- Nausea
- Vomiting
- Mild shortness of breath

Past Medical History

- Type 2 Diabetes Mellitus

Social History

- Active smoker

Current Medications

- Metformin

Vital Signs

| Parameter | Value |
|----------|-------|
| Blood Pressure | 138/86 mmHg |
| Heart Rate | 96 bpm |
| Respiratory Rate | 20/min |
| Temperature | 36.8°C |
| Oxygen Saturation | 97% on room air |

No ECG has yet been performed.

---

# AI Task

You are the emergency physician evaluating this patient.

Provide a structured assessment that includes:

1. Problem representation
2. Initial assessment
3. Prioritized differential diagnosis
4. Life-threatening diagnoses that must be excluded
5. Recommended investigations with justification
6. Immediate evidence-based management
7. Patient disposition
8. Clinical reasoning supporting each decision

Your response should prioritize patient safety and follow current evidence-based clinical practice.

---

# End of AI Prompt

The sections below are intended for physician reviewers and should not be included in the AI prompt.

---
# Gold Standard Physician Response

## 1. Problem Representation

A 39-year-old man with significant cardiovascular risk factors (type 2 diabetes mellitus and active smoking) presents with one hour of acute pressure-like central chest pain radiating to the left shoulder, associated with diaphoresis, nausea, vomiting, and mild dyspnea. The presentation is highly concerning for an acute coronary syndrome, particularly ST-elevation myocardial infarction (STEMI), until proven otherwise.

---

## 2. Initial Assessment

The patient's airway is patent, breathing appears adequate, and circulation is currently stable based on the available vital signs. Although he is hemodynamically stable, this presentation represents a time-critical cardiovascular emergency requiring immediate evaluation and treatment.

Continuous cardiac monitoring, intravenous access, and rapid acquisition of a 12-lead ECG are immediate priorities.

---

## 3. Prioritized Differential Diagnosis

| Priority | Diagnosis | Reason |
|----------|-----------|--------|
| 1 | ST-Elevation Myocardial Infarction (STEMI) | Typical ischemic chest pain with multiple cardiovascular risk factors |
| 2 | Non-ST Elevation Myocardial Infarction (NSTEMI) | Similar presentation if ST elevation is absent |
| 3 | Aortic Dissection | Must always be excluded in severe acute chest pain |
| 4 | Pulmonary Embolism | Dyspnea and chest pain may overlap with ACS |
| 5 | Acute Pericarditis | Less likely but important consideration |
| 6 | Acute Pancreatitis | Epigastric pain and vomiting can mimic ACS |
| 7 | Gastroesophageal Reflux Disease | Diagnosis of exclusion after serious conditions are ruled out |

---

## 4. Immediate Life-Threatening Conditions

The following diagnoses must be rapidly considered and excluded:

- ST-Elevation Myocardial Infarction
- Aortic Dissection
- Pulmonary Embolism
- Cardiac Tamponade
- Tension Pneumothorax
- Massive Arrhythmia

---

## 5. Recommended Investigations

### Immediate

- 12-lead ECG (within 10 minutes)
- High-sensitivity cardiac troponin
- Continuous cardiac monitoring

### Laboratory

- Complete Blood Count
- Serum electrolytes
- Renal function
- Blood glucose
- Coagulation profile

### Imaging

- Chest X-ray

Further imaging (such as CT angiography) should be guided by the evolving differential diagnosis.

---

## 6. Initial Evidence-Based Management

Immediate management includes:

- Activate the acute coronary syndrome pathway if STEMI is confirmed.
- Administer aspirin promptly unless contraindicated.
- Initiate a second antiplatelet agent according to local protocol.
- Obtain early cardiology consultation.
- Prepare for urgent reperfusion therapy if STEMI is confirmed.
- Monitor vital signs continuously.
- Reassess symptoms and ECG findings frequently.

Management should follow current institutional protocols and internationally accepted clinical guidelines.

---

## 7. Patient Disposition

This patient requires urgent admission to a monitored cardiac setting with immediate cardiology involvement.

If STEMI is confirmed, reperfusion therapy should proceed without unnecessary delay according to local resources and guideline recommendations.
---

# Physician Clinical Reasoning

## Why Acute STEMI Is the Leading Diagnosis

Several features strongly increase the probability of an acute ST-elevation myocardial infarction (STEMI):

- Typical pressure-like central chest pain
- Radiation to the left shoulder
- Diaphoresis
- Nausea and vomiting
- Active smoking
- Type 2 diabetes mellitus
- Acute symptom onset
- Presentation consistent with myocardial ischemia

The combination of a typical clinical presentation and multiple cardiovascular risk factors makes acute coronary syndrome the leading diagnosis until proven otherwise.

---

## Why Not Pulmonary Embolism?

Pulmonary embolism remains an important life-threatening diagnosis because chest pain and dyspnea can overlap with acute coronary syndrome.

However, this patient lacks several features that would increase its likelihood, including:

- Sudden unexplained hypoxemia
- Tachycardia out of proportion to pain
- Clinical signs of deep vein thrombosis
- Recent surgery or prolonged immobilization
- Active malignancy

Pulmonary embolism should remain in the differential diagnosis but is currently less likely than STEMI.

---

## Why Not Aortic Dissection?

Acute aortic dissection must always be considered in patients with severe chest pain because delayed diagnosis can be catastrophic.

Features arguing against dissection include:

- No description of tearing or ripping pain
- No radiation to the back
- No pulse deficits
- No neurological deficits
- Hemodynamic stability
- No clinical evidence of acute aortic insufficiency

Despite these findings, clinicians should maintain a low threshold for reconsidering this diagnosis if new clinical information emerges.

---

## Why Early ECG Is Critical

A 12-lead ECG should be obtained within 10 minutes of presentation because:

- It rapidly identifies STEMI.
- It determines eligibility for reperfusion therapy.
- It influences immediate management decisions.
- Delayed ECG acquisition may delay life-saving treatment.

---

## Why Time Matters

Acute myocardial infarction is a time-sensitive emergency.

Early recognition and reperfusion therapy are associated with improved myocardial salvage, preservation of cardiac function, and reduced mortality.

Every minute of unnecessary delay increases the risk of irreversible myocardial injury.

---

## Clinical Pearls

- Treat acute coronary syndrome as the leading diagnosis until excluded.
- Never allow a normal initial appearance to lower clinical suspicion.
- Cardiovascular risk factors substantially increase disease probability.
- Always prioritize life-threatening diagnoses before considering benign causes.
- Reassess continuously as new clinical information becomes available.
