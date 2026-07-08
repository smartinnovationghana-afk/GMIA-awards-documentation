# Audited Financial Statement

***

### Overview

This document describes the user interface of the **Audited Financial Statement** module within The Ghana Chamber of Mines web portal. The module enables authorized users (managers) to create, upload, manage, and track audited financial statement submissions from their respective mining companies.

***

### 1. Audited Financial Statement List (View Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-04 210239.png" alt=""><figcaption></figcaption></figure>

#### 1.1 Page Header

At the top of the content area, the page title **"Audited Financial Statement List"** is displayed in bold, preceded by a back arrow icon (`←`) for navigation to the parent page. To the right of the title, the following controls are available:

* **Search Field**: A text input box with a light gray placeholder text "search", allowing users to filter the list of audited financial statements by relevant keywords.
* **Refresh Button**: A circular refresh icon accompanied by the label "Refresh", enabling users to reload the list to reflect the latest data entries.
* **Add New Button**: A prominent blue button labeled **"+ Add New Audited Financial Statement"**, which navigates the user to the statement creation page.

#### 1.2 Data List

Below the header, a data grid displays previously submitted audited financial statements. The list includes the following column headers, each equipped with sort indicators (up/down arrows) for ascending and descending ordering:

* **Year**: The reporting year for the audited financial statement.
* **Month**: The specific month covered by the financial statement.
* **Company Name**: The name of the mining company that submitted the audited financial statement.
* **Date Created**: The timestamp indicating when the statement record was created in the system.
* **Preview**: Provides access to view or preview the submitted audited financial statement document.

#### 1.3 Empty State

When no audited financial statements exist in the system, the data grid displays an empty state. Centered within the list area is a document inbox icon accompanied by the text **"No data"** in a light gray font. This indicates that no audited financial statements have been submitted or recorded for the current view, prompting the user to initiate a new statement submission.

***

### 2. New Audited Financial Statement (Creation Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-04 210303.png" alt=""><figcaption></figcaption></figure>

#### 2.1 Page Header

The creation page header displays **"New"** in bold, preceded by a back arrow (`←`) for returning to the list view. Adjacent to the title is a **"Draft"** status badge, indicating that the current form is in an unsaved draft state. On the far right, two action buttons are available:

* **Cancel Button**: A white button with a dark border and an "×" icon, labeled "Cancel". Clicking this discards the current draft and returns the user to the previous page.
* **Save Button**: A solid blue button labeled "Save", which commits the draft and creates the audited financial statement record.

#### 2.2 File Information Form

The main content area features a bordered card titled **"File Information"**, containing a structured form with the following fields:

**Upload Year (Required Field)**

A dropdown selection field labeled **"Upload Year"**, marked with a red asterisk (`*`) to denote that it is mandatory. The field presents a downward-facing chevron icon indicating dropdown functionality, allowing the user to select the reporting year from a predefined list.

**Upload Month (Required Field)**

A dropdown selection field labeled **"Upload Month"**, also marked with a red asterisk (`*`) to denote that it is mandatory. The field presents a downward-facing chevron icon indicating dropdown functionality, allowing the user to select the reporting month from a predefined list.

**Description (Optional Field)**

A multi-line text area labeled **"Description"**, providing ample space for the user to enter a detailed summary or contextual information about the audited financial statement. The text area supports multiple lines of input and includes a resize handle at the bottom-right corner for adjusting the field height.

**Upload File (Required Field)**

A file upload section labeled **"Upload File"**, marked with a red asterisk (`*`) to denote that it is mandatory. Below the label is a bordered button labeled **"Click To Upload"**, accompanied by an upload icon (depicting an upward arrow). Clicking this button opens the system's file browser, allowing the user to select a document file for upload.

***
