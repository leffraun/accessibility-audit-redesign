# Keyboard Accessibility Audit

## Test Method

The IRCTC train-search flow was tested using only the keyboard.
No mouse was used.

### Keyboard controls used
- Tab
- Shift + Tab
- Enter
- Arrow keys

## Observations

### 1. Keyboard navigation

- Tab moves forward through the train-search controls.
- Shift + Tab moves backward.
- The currently focused element is visibly highlighted.
- The navigation order generally follows the form.

### 2. Date field

- The date field can be reached using Tab.
- Arrow keys can be used to change the selected date.

### 3. Quota selection

- General quota can be selected normally.
- Some restricted quotas, such as Lower Berth/Sr. Citizen, PWD and Duty Pass, display an informational/eligibility message.

### 4. Focus after quota message

- After dismissing the Lower Berth/Sr. Citizen message using Enter, focus returns to the From field.
- This causes the user to navigate through the form again.
- Repeating the interaction can result in the same behaviour occurring again.

## Initial Impression

Most of the basic train-search form can be operated using the keyboard.
The focus reset after the restricted-quota message needs further investigation
to determine whether it creates an accessibility or usability problem.
