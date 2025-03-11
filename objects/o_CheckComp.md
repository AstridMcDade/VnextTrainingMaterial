---
date: 22/01/2025
uid: o_CheckComp
---

# Check Control Composition

The Check control support the following properties:

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | The text displayed next to the checkbox. | "Dynamic Value," "Runtime Checkbox" |
| ID | A unique identifier for referencing and managing the checkbox. | System-generated or user-defined. |
| Tooltip Text | A descriptive or context-sensitive message shown when hovering over the checkbox. | "This is the column 1 tooltip text." |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Style | Defines the visual appearance of the checkbox, such as background colour. | Example: Red background for emphasis. |
| Visible | Toggles whether the checkbox is displayed or hidden. |  True (visible) or False (hidden). |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Enabled | Determines if the checkbox is interactive. | True: Clickable, False: Disabled. |
| AutoPostBack | Triggers a refresh or updates related controls when the checkbox state changes. | True or False. |
| Checked State | Indicates whether the checkbox is checked (True) or unchecked (False). | True (Checked), False (Unchecked). |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Hover Tooltips | Displays additional information or guidance when the user hovers over the checkbox. | "This is the column 1 tooltip text." |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Control Groups | Check control can be part of a group, allowing shared attributes or operations. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Specifies whether checking the box is mandatory. | True (Required), False (Optional). |
| Error Messages | Displays validation messages when the checkbox is unchecked but required. | Example: "Checkbox selection is required." |
