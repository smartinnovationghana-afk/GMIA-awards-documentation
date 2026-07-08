# Sustainability Report

***

### Overview

This document describes the user interface of the **GCM PR Data Upload** module within The Ghana Chamber of Mines web portal. The module enables authorized users to upload, manage, and track PR (Production/Performance Report) data submissions from their respective mining companies.

***

### 1. PR Data Upload List (View Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-04 203926.png" alt=""><figcaption><p>PR Data Upload List</p></figcaption></figure>

#### 1.1 Page Header

At the top of the content area, the page title **"Pr Data Upload List"** is displayed in bold, preceded by a back arrow icon (`←`) for navigation to the parent page. To the right of the title, the following controls are available:

* **Search Field**: A text input box with a light gray placeholder text "search", allowing users to filter the list of uploaded records by relevant keywords.
* **Refresh Button**: A circular refresh icon accompanied by the label "Refresh", enabling users to reload the list to reflect the latest data entries.
* **Add New Button**: A prominent blue button labeled **"+ Add New Pr Data Upload"**, which navigates the user to the upload creation page.

#### 1.2 Data List

Below the header, a data grid displays previously uploaded PR data entries. The list includes the following column headers:

* **Company Account**: Identifies the mining company associated with the upload. Each column header includes a sort indicator (up/down arrows) for ascending and descending ordering.
* **Year**: The reporting year for the data submission, with sort functionality enabled.
* **Quarter**: The fiscal quarter covered by the upload, with sort functionality enabled.
* **Month**: The specific month of the data submission, with sort functionality enabled.
* **Description**: A free-text field providing context or summary for the upload, with sort functionality enabled.
* **Approval Status**: Indicates the current review state of the submission, with sort functionality enabled whether its PENDING, APPROVED.



When no upload records exist, the data grid displays an empty state. Centered within the list area is a document inbox icon accompanied by the text **"No data"** in a light gray font. This indicates that no PR data uploads have been submitted or recorded for the current view, prompting the user to initiate a new upload.

***

### 2. New PR Data Upload (Creation Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-04 203850.png" alt=""><figcaption><p>Upload PR Data</p></figcaption></figure>

#### 2.1 Page Header

The creation page header displays **"New"** in bold, preceded by a back arrow (`←`) for returning to the list view. Adjacent to the title is a **"Draft"** status badge, indicating that the current form is in an unsaved draft state. On the far right, two action buttons are available:

* **Cancel Button**: A white button with a dark border and an "×" icon, labeled "Cancel". Clicking this discards the current draft and returns the user to the previous page.
* **Save Button**: A solid blue button labeled "Save", which commits the draft and creates the upload record.

#### 2.2 Upload Section

The main content area features a bordered card titled **"Upload PR Data"**, accompanied by a document icon. In the top-right corner of this card, an orange button labeled **"Download Template"** (with a download icon) allows users to retrieve a standardized file template for data preparation.

#### 2.3 File Drop Zone

Centered within the card is a large, dashed-border upload area designed for drag-and-drop functionality. The zone contains:

* An upload icon (depicting a document with an upward arrow) centered within the area.
* Instructional text: **"Click or drag PR data file to upload"**
* File format guidance displayed below in a smaller, lighter font: _"Support for Excel files (.xlsx, .xls) and CSV files. Maximum size 10MB."_

This area accepts direct file selection via click or drag-and-drop interaction. Once a file is selected or dropped, the system processes the upload according to the supported formats and size constraints.

***

