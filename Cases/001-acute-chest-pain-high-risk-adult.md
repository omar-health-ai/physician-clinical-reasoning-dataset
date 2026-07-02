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
## AI Capabilities Being Evaluated

This case evaluates the following Healthcare AI capabilities:

- Clinical reasoning
- Problem representation
- Diagnostic prioritization
- Differential diagnosis generation
- Risk stratification
- Investigation planning
- Evidence-based management
- Patient safety awareness
- Guideline-informed decision making
- Clinical communication

---
## Case Complexity

**Reasoning Level:** Advanced

**Diagnostic Complexity:** High

**Time Sensitivity:** Critical

**Patient Safety Risk:** High

**Evidence Requirement:** High

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

## Clinical Timeline

| Time | Event |
|------|-------|
| 0 min | Chest pain begins while resting |
| 60 min | Patient arrives at the Emergency Department |
| Arrival | Initial assessment and vital signs |
| Within 10 min | ECG should be obtained |
| Immediately after ECG | Clinical decision regarding STEMI pathway |
---

## Clinical Red Flags

This presentation contains several features requiring immediate attention:

- Acute central chest pain
- Radiation to the left shoulder
- Diaphoresis
- Nausea and vomiting
- Cardiovascular risk factors
- Possible acute coronary syndrome

These findings require urgent assessment until a life-threatening cause has been excluded.
---

## Additional Information Needed

The following information is not yet available but would influence clinical decision-making:

- Previous history of coronary artery disease
- Family history of premature cardiovascular disease
- Drug allergies
- Current medications beyond metformin
- ECG findings
- Troponin results
- Previous cardiac investigations
---

## Information Available

- Chest pain
- Radiation
- Diabetes
- Smoking
- Stable vital signs

## Information Not Yet Available

- ECG
- Troponin
- Chest X-ray
- Laboratory investigations
- Previous cardiac history

---

## AI Task

Assume you are the emergency physician responsible for the initial assessment of this patient.

Using only the information provided above:

1. Write a one-sentence problem representation.
2. List your prioritized differential diagnosis.
3. Identify immediately life-threatening conditions.
4. Recommend the initial investigations and explain why each is necessary.
5. Recommend immediate management.
6. State the most appropriate patient disposition.
7. Explain your clinical reasoning.
8. Identify any important missing information that would influence your decision-making.

Your response should be evidence-based, prioritize patient safety, and avoid unsupported assumptions.

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

## Diagnostic Confidence

| Diagnosis | Confidence |
|-----------|-----------|
| STEMI | 95% |
| NSTEMI | 70% |
| Pulmonary Embolism | 35% |
| Aortic Dissection | 20% |
| Pericarditis | 15% |

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

## Patient Safety Checkpoints

Before disposition, confirm:

- ECG reviewed
- STEMI excluded or confirmed
- Cardiology consulted when appropriate
- Hemodynamic status reassessed
- Pain reassessed
- Repeat ECG if symptoms persist
- Troponin trend planned if indicated

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
---

# AI Response Evaluation

The following rubric illustrates how a physician reviewer can evaluate an AI-generated response for this clinical scenario.

| Evaluation Domain | Excellent Response |
|-------------------|-------------------|
| Clinical Accuracy | Correctly identifies acute STEMI as the leading diagnosis while maintaining an appropriate differential diagnosis. |
| Clinical Reasoning | Clearly explains why STEMI is most likely using the patient's history, risk factors, and presentation. |
| Differential Diagnosis | Includes dangerous alternative diagnoses such as pulmonary embolism and aortic dissection and explains why they are less likely. |
| Investigation Strategy | Prioritizes a 12-lead ECG within 10 minutes, cardiac biomarkers, and other appropriate investigations. |
| Evidence-Based Management | Recommends immediate management consistent with current evidence-based practice and institutional protocols. |
| Patient Safety | Recognizes this as a time-critical emergency requiring urgent cardiology involvement and continuous monitoring. |
| Communication | Presents recommendations in a clear, structured, and professional manner. |

---

## Common AI Errors

Examples of responses that should receive lower scores include:

- Failing to recognize acute coronary syndrome as the leading diagnosis.
- Missing life-threatening differential diagnoses.
- Delaying ECG acquisition.
- Suggesting discharge before excluding serious pathology.
- Omitting aspirin or reperfusion planning when appropriate.
- Providing treatment recommendations without clinical reasoning.
- Ignoring cardiovascular risk factors.
- Giving vague or unsupported recommendations.

---

## Reviewer Feedback Example

### Strengths

- Appropriate prioritization of acute coronary syndrome.
- Logical differential diagnosis.
- Safe initial management.
- Well-organized clinical reasoning.

### Areas for Improvement

- More clearly justify exclusion of alternative diagnoses.
- Explain why ECG should be obtained immediately.
- Explicitly discuss reperfusion strategy once STEMI is confirmed.

---

## Overall Assessment

An excellent AI response should demonstrate physician-level clinical reasoning rather than simply listing diagnoses or treatments.

The response should prioritize patient safety, explain its reasoning transparently, and remain consistent with contemporary evidence-based clinical practice.
---

# Teaching Notes

## Key Learning Objectives

After completing this case, learners should be able to:

- Recognize the classical presentation of acute ST-elevation myocardial infarction (STEMI).
- Develop a structured differential diagnosis for acute chest pain.
- Prioritize life-threatening diagnoses before considering less serious conditions.
- Select appropriate initial investigations based on clinical reasoning.
- Apply evidence-based emergency management principles.
- Appreciate the importance of time-sensitive reperfusion therapy.
- Evaluate AI-generated medical responses using a structured physician framework.

---

## Key Clinical Takeaways

- Chest pain should always be approached systematically.
- Acute coronary syndrome remains a clinical diagnosis until excluded.
- Early ECG acquisition is one of the highest-priority investigations.
- Risk factors significantly alter pre-test probability.
- Every patient with suspected ACS deserves rapid reassessment.
- Good clinical reasoning is transparent, evidence-based, and patient-centered.

---

## Common Learner Mistakes

- Prematurely diagnosing benign chest pain.
- Forgetting dangerous differential diagnoses.
- Delaying ECG acquisition.
- Ordering investigations without a clear clinical question.
- Failing to prioritize immediate management.
- Anchoring on a single diagnosis too early.

---
# Healthcare AI Evaluation Objectives

This case is designed to evaluate whether an AI system can:

- Produce an accurate problem representation.
- Prioritize life-threatening diagnoses.
- Generate an appropriate differential diagnosis.
- Recommend evidence-based investigations.
- Select safe initial management.
- Identify diagnostic uncertainty.
- Communicate reasoning transparently.
- Avoid unsafe recommendations.
---

# Dataset Annotation Summary

| Attribute | Value |
|-----------|-------|
| Primary Diagnosis | ST-Elevation Myocardial Infarction (STEMI) |
| Clinical Specialty | Emergency Medicine |
| Clinical Domain | Cardiology |
| Reasoning Complexity | Advanced |
| Patient Safety Risk | Critical |
| Time Sensitivity | Immediate |
| Guideline Requirement | High |
| Educational Value | High |
| AI Evaluation Difficulty | Advanced |
---

## Discussion Questions

1. Which historical features most strongly supported STEMI?
2. Why should pulmonary embolism remain in the differential diagnosis?
3. Why is early ECG acquisition essential?
4. Which findings would increase suspicion for aortic dissection?
5. How would your management change if the patient became hypotensive?

---

# Key Clinical Pearls

- Acute coronary syndrome should remain the leading working diagnosis until objective evidence suggests otherwise.
- Time-sensitive conditions require early recognition and rapid escalation.
- Clinical reasoning should remain dynamic as new information becomes available.
- Safe physicians and safe AI systems avoid premature diagnostic closure.
- Diagnostic certainty evolves with additional clinical data.

---
Diagnostic Reasoning Flow
Chest Pain
      │
      ▼
Life-threatening causes?
      │
      ▼
ECG within 10 minutes
      │
      ▼
STEMI?
      │
 ┌────┴────┐
 │         │
YES       NO
 │         │
Reperfusion Continue evaluation
---

## Key Messages

- Chest pain requires systematic evaluation.
- Always prioritize life-threatening diagnoses.
- Early ECG acquisition is essential.
- Clinical reasoning should remain transparent.
- Patient safety takes priority over diagnostic certainty.

---
# References

This educational case is based on principles of evidence-based clinical practice.

Clinicians should always consult the latest versions of relevant international and local guidelines when making patient-care decisions.

Examples include:

- American Heart Association (AHA)
- European Society of Cardiology (ESC)
- National Institute for Health and Care Excellence (NICE)
- American College of Cardiology (ACC)

---
# Version History

| Version | Status | Description |
|----------|--------|-------------|
| v0.1 | Released | Initial clinical scenario |
| v0.2 | Released | AI Task added |
| v0.3 | Released | Gold Standard Physician Response |
| v0.4 | Released | Clinical Reasoning |
| v0.5 | Released | AI Evaluation |
| v0.6 | Released | Teaching Notes |
| v0.7 | Released | Healthcare AI Evaluation |
| v1.0 | Released | First complete flagship case |

---

**Project:** Physician Clinical Reasoning Dataset (PCRD)

**Author:** Dr. Omar Shoeib, MD

**License:** MIT
