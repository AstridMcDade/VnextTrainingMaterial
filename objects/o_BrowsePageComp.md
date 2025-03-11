---
date: 22/01/2025
uid: o_BrowsePageComp
---

# Browse Page Control Composition

The Browse Page properties enable the browse page to be flexible, interactive, and contextually dynamic while ensuring usability and task completion.

Browse Pages support the following properties:

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | Displays the name of the browse page or context-specific information. | "Dynamic Value," "Tooltip Text." |
| ID | A unique identifier for the browse page. | Configurable. |
| Tooltip Text | Provides context-sensitive help displayed when hovering over the browse page icon or text box. | Configurable. |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Resizable | Indicates whether the browse page can be resized by dragging its edges. | True or False |
| Page Height | Sets the height of the browse page in pixels. | Configurable. |
| Page Width | ets the width of the browse page in pixels. | Configurable. |
| Show Textbox | Toggles whether a related text box is visible or hidden. | True or False |
| Visible | Toggles the visibility of the browse page itself. | True or **False |

## Data Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Dynamic Value | The value dynamically updated in the associated text box upon selection. | Configurable. |
| Default-To Value | The pre-configured default value displayed in the text box. | Configurable. |
| Page Definition | Determines the type or source of data displayed in the browse page | "Set 1 (Original)" or "Set 2 (Participants)." |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Indicates whether selecting a value in the browse page is mandatory before submitting the task. | True or False |
| AutoPostBack | Triggers a refresh of the page or updates other fields when a value is selected. | True or False |
| Index | Allows changing the order or position of the browse page in the interface. | Configurable. |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Selection Mechanism | Allows users to select values (e.g., names, participants) from a tabular list. | Configurable. |
| Hover Tooltips | Displays additional information or guidance when the user hovers over an icon or text box. | Configurable. |
| Close Action | Clicking a close (X) button dismisses the browse page window. | Enabled. |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Control Groups | Browse pages can be part of a group, allowing shared attributes or operations. | e.g., adding/deleting rows |
| Controls | Includes Value, Unconfigured, Empty, Dynamic Value, Default-To Value, Tooltip Text, etc., within the group. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Error Messages | Displays validation messages (e.g., "Required Field is a required field") when conditions are unmet. | Configurable. |
| Pending Tasks | Changes made in the browse page can generate or update tasks for further action. | Enabled. |
