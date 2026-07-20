# Legal Cases

***

## Legal Cases Module — User Interface Documentation

### Overview

This document describes the user interface of the **Legal Cases** module within The Ghana Chamber of Mines web portal. The module enables authorized users (managers) to create, manage, and track legal cases involving their respective mining companies. The module provides both a list view for monitoring all cases and a detailed creation form for entering new legal case information.

***

### 1. Legal Cases List (View Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-20 200217.png" alt=""><figcaption><p>Legal Cases List</p></figcaption></figure>

#### 1.1 Page Header

At the top of the content area, the page title **"Legal Cases List"** is displayed in bold, preceded by a back arrow icon (`←`) for navigation to the parent page. To the right of the title, the following controls are available:

* **Search Field**: A text input box with a light gray placeholder text "search", allowing users to filter the list of legal cases by relevant keywords.
* **Refresh Button**: A circular refresh icon accompanied by the label "Refresh", enabling users to reload the list to reflect the latest data entries.
* **Add New Button**: A prominent dark red button labeled **"+ Add New Legal Case"**, which navigates the user to the legal case creation page.

#### 1.2 Data List

Below the header, a data grid displays legal case records. The list includes the following column headers, each equipped with sort indicators (up/down arrows) for ascending and descending ordering:

* **Case Number**: The unique identifier assigned to each legal case.
* **Case Title**: The title or name of the legal case.
* **Case Type**: The classification or category of the legal case.
* **Case Status**: The current state or progress of the legal case.

#### 1.3 Empty State

When no legal case records exist in the system, the data grid displays an empty state. Centered within the list area is a document inbox icon accompanied by the text **"No data"** in a light gray font. This indicates that no legal cases have been created or recorded for the current view.

***

### 2. New Legal Case (Creation Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-20 200306.png" alt=""><figcaption><p>Legal Cases Detaila</p></figcaption></figure>

#### 2.1 Page Header

The creation page header displays **"New"** in bold, preceded by a back arrow (`←`) for returning to the list view. Adjacent to the title is a **"Draft"** status badge, indicating that the current form is in an unsaved draft state. On the far right, two action buttons are available:

* **Cancel Button**: A white button with a dark border and an "×" icon, labeled "Cancel". Clicking this discards the current draft and returns the user to the previous page.
* **Save Button**: A solid dark red button labeled "Save", which commits the draft and creates the legal case record.

#### 2.2 Legal Case Details Form

The main content area features a bordered card titled **"Legal Case Details"**, containing a structured form with the following fields:

**Case Number (Required Field)**

A text input field labeled **"Case Number"**, marked with a red asterisk (`*`) to denote that it is mandatory. This field accepts alphanumeric input for the unique case identifier.

**Case Title (Optional Field)**

A text input field labeled **"Case Title"**, allowing the user to enter a descriptive title for the legal case.

**Case Type (Optional Field)**

A dropdown selection field labeled **"Case Type"** with a placeholder text "Select Case Type" and a downward-facing chevron icon. This field allows the user to classify the legal case from a predefined list of case categories.

**Case Status (Optional Field)**

A dropdown selection field labeled **"Case Status"** with a downward-facing chevron icon. This field allows the user to indicate the current state of the legal case from a predefined list of status options.

**Case Description (Optional Field)**

A multi-line text area labeled **"Case Description"**, providing ample space for the user to enter a detailed narrative or contextual information about the legal case. The text area supports multiple lines of input and includes a resize handle at the bottom-right corner for adjusting the field height.

**Documents (Optional Field)**

A file upload section labeled **"Documents"**. Below the label is a bordered button labeled **"Select Files"**, accompanied by an upload icon (depicting an upward arrow). Clicking this button opens the system's file browser, allowing the user to select and attach supporting documents to the legal case record.
