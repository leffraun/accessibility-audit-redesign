# Screen Reader Accessibility Audit

## Objective

To examine whether the IRCTC train-search interface can be understood and operated using a screen reader.

## Testing Setup

- Screen reader: NVDA
- Browser: Chrome
- Navigation method: Keyboard
- Test area: IRCTC website and train-search interface

## Initial Observations

### 1. Website Logo

**Action:** Pressed Ctrl + Home.

**NVDA announcement:** "Official Indian Railway and Catering Portal."

**Observation:** The logo is announced with meaningful descriptive text.

### 2. PNR Status Link

**Action:** Pressed Tab.

**NVDA announcement:** "Link, PNR Status, opens new window."

**Observation:** NVDA identifies the element as a link, announces its name and indicates that it opens a new window.

### 3. Reservation Chart Link

**Action:** Pressed Tab again.

**NVDA announcement:** "Link, Reservation Chart, website will open in new tab."

**Observation:** NVDA identifies the element as a link, announces its name and indicates that it opens in a new tab.

## Further Testing

- Continue keyboard navigation towards the train-search form.
- Inspect form labels and accessible names.
- Test date and quota controls.
- Investigate error-message announcements.
