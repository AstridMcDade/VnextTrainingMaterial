---
date: 22/01/2025
uid: o_ButtonComp
---

# Button Control Composition

A Button control includes several properties that define its functionality, appearance, and behaviour. The Button supports the following properties:

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | Displays the text visible on the button. | Configurable. |
| ID | A unique identifier for the button. | System-generated or user-defined. |
| Tooltip Text | Provides a context-sensitive help message when hovered over. | "This is the button tooltip text." |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Style | Defines the button's appearance (e.g., background colour, text style). | Example: Red background. |
| Visible | Controls the visibility of the button. | **True** (visible) or **False** (hidden)|

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Enabled | Indicates whether the button is active and clickable. | **True**: Interactive, **False**: Disabled. |
| Click Action | The functionality or event triggered when the button is clicked (unconfigured buttons have no action). | Configurable. |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Hover Tooltips | Displays additional information or guidance when the user hovers over an icon or text box. | "This is the button-runtime tooltip text". |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Control Groups | Buttons can belong to a group, sharing attributes or actions. | Example: Text, value fields. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Pending Tasks | Button actions may generate system tasks or updates. | Configurable. |
| Reset Functionality | Allows reverting to default configurations | Enabled. |
| Column and Span Settings | Buttons can be resized or repositioned within their container. | Configurable. |
