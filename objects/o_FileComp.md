---
date: 23/01/2025
uid: o_FileComp
---

# File Attachement Control Composition

A File Control is an interactive UI component that allows users to upload, manage, and interact with file attachments. It supports various properties that define its identification, appearance, behaviour, and validation.

## Identification Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Title/Caption | Displays the label or name of the file control. | "Runtime File," "Grid File." |
| ID | A unique identifier for referencing and managing the file control. | System-generated or user-defined. |
| Tooltip Text | Displays context-sensitive help when hovering over the file control. | "This is the file tooltip text." |

## Display Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Style | Defines the visual appearance of the file control (e.g., highlighted background). | Example: Red background. |
| Visible | Controls whether the file control is displayed or hidden. | True (visible) or False (hidden). |

## Data Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Dynamic Value | The default or current file attached dynamically. | Configurable. |
| Default-To Value | A predefined file displayed when no selection is made. | Configurable. |
| Number of Uploads | Specifies the maximum number of files that can be uploaded. | Example: 5 files per upload. |
| File Size Limit | Defines the maximum allowable file size for uploads. | Example: 10KB. |
| Upload To | Determines the storage location for uploaded files. | Options: File System, Database, Azure File Storage. |

## Behavioural Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| AutoPostBack | Triggers a refresh or updates other fields when a file is uploaded. | True or False. |
| Enabled | Indicates whether the file control is interactive. | True: Clickable, False: Disabled. |
| Index | Controls the file control’s position within an interface. | Configurable. |

## Interaction Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| File Selection | Allows users to choose a file from their system for upload. | Configurable. |
| Remove File | Provides an option to delete an attached file. | Enabled. |
| Hover Tooltips | Displays additional guidance when the user hovers over the file control. | "This is the file tooltip text." |

## Grouping Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Object Groups | File controls can be grouped for shared attributes or behaviours. | Configurable. |
| Control Groups | Allows file controls to be linked with other controls like dropdowns or buttons. | Configurable. |

## Validation Properties

| Property | Description | Value |
| ---- | ---- | ---- |
| Required Field | Ensures that a file is uploaded before proceeding. | True (Required), False (Optional). |
| Error Messages | Displays validation errors when no file is uploaded. | Example: "File is a required field." |
