---
date: 23/01/2025
uid: o_LabelComp
---

# Label Control Composition

A Label Control is a UI component used to display static or dynamic text within an interface. It provides contextual information, tooltips, and reference values while supporting properties for identification, formatting, and visibility.

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | Displays the label or name associated with the control. | "Reference Label Text Value", "New Label". |
| ID | A unique identifier for referencing and managing the label. | System-generated or user-defined. |
| Tooltip Text | Displays context-sensitive help when hovering over the label. | "This is the label tooltip text." |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Style | Defines the visual appearance of the label (e.g., background, font style). | Example: Bold, Red background. |
| Width | Specifies the horizontal size of the label control. | Configurable (e.g., 100px, 180px). |
| Visible | Controls whether the label is displayed or hidden. | True (visible) or False (hidden). |

## Data Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Dynamic Value | Displays dynamically generated text. | Example: "This is the Dynamic Value". |
| Default-To Value | A predefined value shown when no other value is assigned. | Example: "This is the fcDefaultTo Value". |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| AutoPostBack | Triggers a refresh or updates when the label value changes. | True or False. |
| Index | Controls the label’s position within an interface. | Configurable. |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Hover Tooltips | Displays additional guidance when hovering over the label. | "This is the label tooltip text." |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Object Groups | Labels can be grouped for shared attributes or behaviours. | Configurable. |
| Control Groups | Allows labels to be linked with other controls like text boxes or dropdowns. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Ensures that a label is displayed before proceeding. | True (Required), False (Optional). |
| Error Messages | Displays validation errors when a required label is missing. | Example: "Label is a required field." |
