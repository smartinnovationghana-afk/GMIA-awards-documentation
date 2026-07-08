# Security Reports

***

### Overview

This document describes the user interface of the **Security Reports** module within The Ghana Chamber of Mines web portal. The module enables authorized users (managers) to browse, search, and manage security-related incident reports submitted by their respective mining companies. The data displayed in this module originates from the **Incident Report (Upload)** module, where individual incident records are first captured and submitted.

***

### 1. Data Source

The information presented in the Security Reports module is sourced from the **Incident Report (Upload)** module. Individual incident records uploaded through that module are aggregated and displayed here, providing a consolidated view of security-related occurrences across reporting periods.

### 2. Security Reports List (View Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-05 184836.png" alt=""><figcaption><p>Security Report List</p></figcaption></figure>

#### 2.1 Page Header

At the top of the content area, the page title **"Security Reports List"** is displayed in bold, preceded by a back arrow icon (`←`) for navigation to the parent page. To the right of the title, the following controls are available:

* **Search Field**: A text input box with a light gray placeholder text "search", allowing users to filter the list of security reports by relevant keywords.
* **Refresh Button**: A circular refresh icon accompanied by the label "Refresh", enabling users to reload the list to reflect the latest data entries.

#### 2.2 Data List

Below the header, a data grid displays security incident reports. The list includes the following column headers, each equipped with sort indicators (up/down arrows) for ascending and descending ordering:

* **Company Name**: The name of the mining company associated with the security incident report.
* **Year**: The reporting year for the security incident.
* **Month**: The specific month during which the security incident occurred or was reported.
* **Quarter**: The fiscal quarter corresponding to the reporting period.
* **Security Issue**: A classification or description of the type of security incident recorded.
* **Occurrences**: The number of times the specified security issue was reported within the given period.



When no security reports exist in the system, the data grid displays an empty state. Centered within the list area is a document inbox icon accompanied by the text **"No data"** in a light gray font. This indicates that no security incident reports have been submitted or recorded for the current view.

***
