---
date: 23/01/2025
uid: o_LinkComp
---

# Link Control Composition

A Link Control is an interactive UI element that allows users to navigate to external or internal destinations when clicked. It supports configurable properties related to identification, behaviour, and display, ensuring controlled navigation and accessibility.

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | Displays the label or name associated with the link. | "Click Here," "Runtime Link." |
| ID | A unique identifier for referencing and managing the link control. | System-generated or user-defined. |
| Tooltip Text | Displays context-sensitive help when hovering over the link. | "This is a tooltip for the link." |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Style | Defines the visual appearance of the link (e.g., text colour, underline style). | Example: Bold, Blue text. |
| Visible | Controls whether the link is displayed or hidden. | **True** (visible) or **False** (hidden). |

## Data Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Navigate URL | The destination URL that the link redirects to. | Example: <https://www.google.com>. |
| Image URL | Displays an image that acts as a clickable link. | Example: Web Navigator Dashboard. |
| Text | The text that appears as the hyperlink. | Example: "Test Link". |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| AutoPostBack | Triggers a refresh or updates when the link is clicked. | **True** or **False**. |
| Index | Controls the link’s position within an interface. | Configurable. |
| Target Self | Determines whether the link opens in the same window or a new tab. | **Same Window** or **New Tab**. |
| Enabled | Indicates whether the link is active or disabled. | **True** (Clickable), **False** (Disabled). |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Hover Tooltips | Displays additional guidance when hovering over the link. | "This is a tooltip for the link." |
| Click Action | Defines the action performed when the link is clicked. | Example: Redirects to a new page. |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Object Groups | Links can be grouped for shared attributes or navigation logic. | Configurable. |
| Control Groups | Allows links to be linked with other controls like buttons or text fields. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Ensures that a valid link is assigned before proceeding. | **True** (Required), **False** (Optional). |
| Error Messages | Displays validation errors when no valid URL is provided. | Example: "This link is required." |
