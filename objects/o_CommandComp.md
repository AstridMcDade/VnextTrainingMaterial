---
date: 23/01/2025
uid: o_CommandComp
---

# Command Control Composition

The Command control support the following properties:

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Label | Displays a default value that uniquely identifies the command control. | Configurable. |
| ID | A unique identifier for referencing and managing the command control. | System-generated or user-defined. |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Caption Textbox | Configures the text displayed on the command button. | Configurable. |
| Tooltip Text | A text field to define tooltips displayed when hovering over the command button or control. | "This is the command tooltip text." |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Column Dropdown | Determines the behaviour of associated controls, such as button positioning or other dynamic changes. | Configurable. |
| Index Checkbox| Affects the position of buttons (e.g., moves the "Done" button relative to other controls). | **True** or **False** |
| Pending Task Creation | Triggers the generation of tasks linked to the command. | Enabled or Disabled |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Command Buttons | Interactive elements like "Start," "Done," or custom buttons that trigger specific actions. | Configurable. |
| Show Branch History Link | Allows users to open a history window displaying previously executed commands or tasks. | Enabled. |
| Reset Button | Restores the page or form to its original state. | Enabled. |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Process Groups | Categorises and organises commands within logical groups for easier navigation. | Configurable. |
| Attributes Section |  Groups configurable fields for managing required validation, tooltips, and values. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Ensures specific fields are populated before an action can proceed. | **True** (Required), **False** (Optional). |
| Error Messages | Displays context-specific validation errors, such as "Required is a required field" or "Please select a valid command to continue the process." | Configurable. |
