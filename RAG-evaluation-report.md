# CareMate AI – RAG Evaluation Report

## 1. Purpose

This report documents manual testing of CareMate AI's Retrieval-Augmented Generation (RAG) behaviour using a fictional hospital knowledge base.

**Important:** St. Aurelia Memorial Hospital is fictional. All hospital information used in these tests is sample data, not real medical or hospital information.

## 2. Testing Scope

A total of 7 scenarios were manually tested to evaluate information retrieval, answer accuracy, source grounding, emergency handling, and responses to missing information.

## 3. Test Results

| Test Scenario | Observed Result | Status |
|---|---|---|
| OPD timings | Correct timings were retrieved in a later test. Conflicting timing documents were identified during initial testing. | Passed with issue |
| General Physician consultation fee | Correctly answered ₹500 per visit using the knowledge base. | Passed |
| Cancellation and rescheduling | Response matched the relevant policy information. | Passed |
| Appointment preparation | Correct preparation instructions were retrieved. An unrelated knowledge-base excerpt was also retrieved. | Passed with issue |
| Emergency routing | Recommended immediate emergency care for symptoms suggesting a possible emergency. | Passed |
| Medical speciality guidance | Suggested Neurology and General Medicine without making a diagnosis. | Passed |
| Missing ambulance information | Correctly stated that ambulance details could not be verified from available documents. | Passed |

## 4. Observed Strengths

- Retrieved information from the hospital knowledge base.
- Provided source references in responses.
- Followed non-diagnostic guidance for medical queries.
- Recognised emergency-related queries and recommended urgent care.
- Avoided inventing information when details were unavailable.

## 5. Issues Identified

1. Conflicting hospital timing information appeared in different knowledge-base documents.
2. An unrelated knowledge-base excerpt appeared during appointment preparation testing.
3. Temporary model service and rate-limit errors affected response reliability.
4. The emergency number 911 in sample content is not localised for an India-based deployment.
5. Live doctor availability and appointment booking are not verified or connected to real hospital systems.

## 6. Limitations

- Testing used fictional hospital data.
- Evaluation was manual and limited to seven scenarios.
- No quantitative retrieval or answer-quality benchmark was conducted.
- No real hospital integration or clinical validation was performed.
- The current prototype is not production-ready.

## 7. Recommended Improvements

- Remove conflicting and duplicate knowledge-base information.
- Introduce document versioning and source-priority rules.
- Improve retrieval relevance and reduce unrelated chunks.
- Evaluate retrieval precision,
