# Visual Accessibility Audit

## Objective

To examine the visual accessibility of the IRCTC train-search interface, focusing on text readability, contrast, form labels and the use of colour.

## Method

- Inspected the train-search interface visually.
- Checked whether important form controls and labels were easy to identify.
- Looked for information communicated through colour.
- Contrast measurements are pending.

## Initial Observations

### 1. Text Readability

**Observation:** The text appeared easy to read during the initial inspection.

**Further investigation:** Measure the contrast ratio of representative text and background combinations against the relevant WCAG requirements.

**Status:** Not yet verified against contrast requirements.

### 2. Labels and Controls

**Observation:** The From, To, date, quota and Search controls appeared easy to identify visually.

**Further investigation:** Inspect form labels, required-field indicators and button/link distinctions. Screen-reader labelling will be examined separately.

**Status:** Initial visual observation only.

### 3. Use of Colour

**Observation:** It was not yet clear whether any information depended on colour alone.

**Further investigation:** Inspect selected options, validation messages, warnings and status indicators for additional visual or textual cues.

**Status:** Requires further investigation.

## Limitations

These observations are based on an initial visual inspection. No contrast ratios have yet been recorded, and the observations do not establish WCAG compliance or non-compliance.

## Next Steps

- Measure representative text contrast.
- Investigate any colour-dependent information.
- Record specific examples and screenshots where relevant.
- Map verified findings to the appropriate WCAG criteria.
## Additional Observations

### 1. CTA Buttons

**Observation:** CTA buttons use orange or blue backgrounds with white text.

**Initial assessment:** The text appears readable during visual inspection. The contrast ratio has not yet been measured for both colour combinations.

**Next step:** Measure the contrast of the white text against each background colour.

### 2. Form Fields

**Observation:** Most form fields appear to be prefilled or populated by default. The From and To fields are the main empty fields available for testing.

**Initial assessment:** The form appeared to work normally during the inspection.

**Next step:** Inspect the From and To fields for clear labels, visible instructions and understandable behaviour when left empty or given invalid input.

### 3. Text Readability

**Observation:** Text across the inspected interface appeared easy to read.

**Limitation:** This is a subjective visual observation and does not replace a contrast-ratio measurement.

### 4. Empty-Field Validation

**Test:** Attempted to search with the From and To fields empty.

**Observation:**
- An error message appears in a red box at the top-right of the form section.
- The message indicates that an error has occurred but does not identify the missing fields or explain how to correct the problem.
- The message remains visible for approximately 10 seconds before disappearing.
- I could not move keyboard focus to the message using Tab.

**Potential usability impact:** Users may struggle to identify and correct the error. The message may disappear before users have enough time to understand it, particularly if they need additional time to read or process the information.

**Relevant heuristic:** Nielsen heuristic 9 — Help users recognize, diagnose and recover from errors.

**Potential WCAG references:**
- SC 3.3.1 — Error Identification.
- SC 4.1.3 — Status Messages, if applicable to how the message is implemented.

**Status:** Potential issue; further testing required.

**Potential improvement:** Identify the missing fields, explain how to correct the error, and investigate whether the message is announced by assistive technology. Consider keeping the error visible until it is corrected or otherwise acknowledged.

**Additional observation:** After the error message disappears, the form remains unchanged. The From and To fields remain empty, and no other visible indication explains what needs to be corrected.

**Further investigation needed:** Determine whether a screen reader announces the error message and whether the message is programmatically associated with the relevant fields.

**Suggested redesign direction:** Provide a specific, persistent error message that identifies the missing fields and explains the corrective action.



