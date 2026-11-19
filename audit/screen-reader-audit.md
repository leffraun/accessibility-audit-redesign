# Screen Reader Accessibility Audit

## Objective

To examine whether the IRCTC train-search interface can be understood and operated using a screen reader.

## Testing Setup

Screen reader: Windows Narrator
Browser: Google Chrome
Navigation: Keyboard and mouse (separate observations)

## Initial Observations

### 1. Website Logo

**Action:** Pressed Ctrl + Home.

**Windows Narrator announcement:** "Official Indian Railway and Catering Portal."

**Observation:** The logo is announced with meaningful descriptive text.

### 2. PNR Status Link

**Action:** Pressed Tab.

**Windows Narratorannouncement:** "Link, PNR Status, opens new window."

**Observation:** NVDA identifies the element as a link, announces its name and indicates that it opens a new window.

### 3. Reservation Chart Link

**Action:** Pressed Tab again.

**Windows Narrator announcement:** "Link, Reservation Chart, website will open in new tab."

**Observation:** NVDA identifies the element as a link, announces its name and indicates that it opens in a new tab.

### 4. Train Search Form

**From field**
- Windows Narrator announces "From station".
- Identifies the field as an input.
- Announces that the input is mandatory.
- Indicates that it has a popup.

**To field**
- Windows Narrator announces "Enter To station".
- Identifies the field as an input.
- Announces that the input is mandatory.
- Indicates that it has a popup.

**Date field**
- Announces the expected date format (DD/MM/YYYY).
- Announces date information.
- The calendar is identified as a table with 6 rows and 7 columns.

**Classes control**
The Classes control was not clearly announced when reached through keyboard navigation. When using the mouse to hover over the control, Narrator recognised the popup and its highlighted selection. Further investigation is required to determine whether this is a keyboard accessibility issue or a screen-reader interaction issue.

**Further investigation required:** Determine whether NVDA announces the currently focused option and selected value when navigating the Classes popup using only the keyboard.



## Further Testing

- Continue keyboard navigation towards the train-search form.
- Inspect form labels and accessible names.
- Test date and quota controls.
- Investigate error-message announcements.
