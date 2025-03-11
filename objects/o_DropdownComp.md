---
date: 23/01/2025
uid: o_DropdownComp
---

# Dropdown Control Composition

A Dropdown Control is an interactive UI component that allows users to select a value from a predefined list. It supports various properties that define its identification, appearance, behaviour, and validation.

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | Displays the label or name of the dropdown control. | "Dynamic Value," "Tooltip Text." |
| ID | A unique identifier for referencing and managing the dropdown. | System-generated or user-defined. |
| Tooltip Text | Displays context-sensitive help when hovering over the dropdown. | "This is the dropdown tooltip text." |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Style | Defines the visual appearance of the dropdown (e.g., background colour). | Example: Red background for emphasis. |
| Width | Specifies the horizontal size of the dropdown control. | Configurable (e.g., 200px). |
| Visible | Controls whether the dropdown is displayed or hidden. | True (visible) or False (hidden). |

## Data Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Dynamic Value | The default or current value selected dynamically. | Configurable. |
| Default-To Value | A predefined value displayed when no selection is made. | Configurable. |
| Items | The list of selectable options in the dropdown menu. | Example: "One; Two; Three; Four; Five". |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| AutoPostBack | Triggers a refresh or updates other fields when a value is selected. | True or False. |
| Enabled | Indicates whether the dropdown is interactive. | True: Clickable, False: Disabled. |
| Index | Controls the dropdown's position within an interface. | Configurable. |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Selection Mechanism | Allows users to select a value from a dropdown list. | Configurable. |
| Hover Tooltips | Displays additional guidance when the user hovers over the dropdown. | "This is the dropdown tooltip text." |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Object Groups | Dropdown controls can be grouped for shared attributes or behaviours. | Configurable. |
| Control Groups | Allows dropdowns to be linked with other controls like text boxes or buttons. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Ensures that a value is selected before proceeding. | True (Required), False (Optional). |
| Error Messages | Displays validation errors when no selection is made. | Example: "Required Field is a required field." |
