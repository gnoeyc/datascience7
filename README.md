# datascience7
**Final Project Pitch**

CT scan is an integral part of disease investigation and follow up for patients admitted in the hospital. It is the role of the radiology department to screen though the scan requests, decide which scans are more urgent and allocate the appropriate resources to complete the scan. The project aims to study the trends of inpatient CT scans, in particular comparing the requested priority of scans vs amended priority, the proportion of scans with significant findings, the features of scans in relation to requesting clinical discipline, time from request to scan and report and after office hours patterns.

**Final Project Proposal**

1. Problem Statement:
The radiology department has an important role in managing scan request and throughput of CT scans for warded patients in the hospital. The challenge is to maximise efficency, balance manpower and equipment requirements while maintaining patient safety standards. By reviewing the characteristics of scan requests, priority assessment, temporal differences and department response time, the study aims to improve the workflow of inpatient CT scans.

2. Hypothesis:
- Clinician ordered scan priority is seldom concordant to radiology perceived priority during office hours.
- Scans tagged as urgent by radiology tend to have more critical findings.
- Scans from some disciplines tend to have more critical findings.
- The department can perform and report the scans within period required as for priority status.
- After office hours scans are generally similar in number and type.


3. Aim:
- Predict scan priority through machine learning.
- Understand staffing requirements at different times.
- Predict requirements for after office hour requests.


4. Limitations:
- After office hour scans currently are mostly vetted by on call radiologists, verbally discussed with clinicians.
- Some routinely scheduled scans are performed after office hours and are screened by radiologists on call.
- Need to anonymise patient data, and will need IRB before more datasets can be obtained (pilot study currently)
- Does not take into account MRI and US load on call. CT scans in emergency department not included.
- Non-standardised vetting of priorities.


5. Dataset:
- A whole month anonymised data of all CT scans done for inpatients of SGH.
