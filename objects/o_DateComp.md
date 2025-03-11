---
date: 23/01/2025
uid: o_DateComp
---

# Date Control Composition

A Date Control is a user interface (UI) element for selecting and managing date inputs. It supports several properties defining its functionality, appearance, and behaviour. Below is the breakdown of its properties:

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| ID | A unique identifier for the date control. | ---- |
| Name | A unique name identifying the date control. | ---- |
| Caption | Displays the label above or near the control. | Configurable to user needs. |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Tooltip Text | Displays contextual information when the user hovers over. | "This is the runtime tooltip text." |
| Style | Customises the appearance (e.g., background colour). | Red background for emphasis. |
| Width | Specifies the horizontal size of the control. | Configurable (e.g., 200px). |
| Display Mask | Formats the display of the input value. | dd/MM/yyyy, yyyy-MM-dd. |

## Data Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Value | Stores the current date input by the user. | Configurable as per input. |
| Dynamic Value | Populated dynamically based on triggers or user interactions. | Default: Current system date. |
| Default-To Value | Holds predefined default values for the control. | Configurable. |
| Input Mask | Specifies the acceptable format for date input. | yyyy/MM/dd. |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| AutoPostBack | Triggers a page refresh or action upon value change. | Enabled or Disabled. |
| Enabled | Indicates whether the control is active or disabled. | True: Active. False: Disabled. |
| Visible | Controls the visibility of the date control. | True: Shown. False: Hidden. |
| Span | Defines the number of columns the control spans. | Configurable. |
| Index | Alters the control's position within a group. | Configurable. |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Calendar Picker | Provides an interface to select a date from a calendar popup. | Opens on interaction. |
| Hover Tooltips | Displays additional guidance when hovering over the control. | "This is the tooltip text." |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Object Group | Groups multiple controls (e.g., Dynamic Value, Default-To Value) for shared operations. | Configurable. |
| Process Groups | Organises controls into logical categories. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field Validation| Ensures that a value is entered before proceeding. | True: Mandatory. False: Optional. |
| Error Messages | Displays validation feedback for missing or incorrect inputs. | Example: "Required Field is a required field." |
| Reset Functionality | Reverts the control to its default state. | Configurable |
