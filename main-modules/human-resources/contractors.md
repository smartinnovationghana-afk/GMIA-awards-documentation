# Contractors

***

## Contractors Module — User Interface Documentation

### Overview

This document describes the user interface of the **Contractors** module within The Ghana Chamber of Mines web portal. The module enables authorized users (managers) to browse, search, and analyze contractor workforce composition data submitted by their respective mining companies. The data displayed in this module originates from the **HR Statistics** section under Data Upload, where contractor statistics are first captured and submitted.

***

### 1. Contractors List (View Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-20 185559.png" alt=""><figcaption></figcaption></figure>

#### 1.1 Page Header

At the top of the content area, the page title **"Contractors List"** is displayed in bold, preceded by a back arrow icon (`←`) for navigation to the parent page. To the right of the title, the following controls are available:

* **Filter by Company Dropdown**: A dropdown selection field labeled "Filter by Company" with a downward-facing chevron icon, allowing users to narrow the displayed records to a specific mining company.
* **Search Field**: A text input box with a light gray placeholder text "search", allowing users to filter the list of contractor records by relevant keywords.
* **Refresh Button**: A circular refresh icon accompanied by the label "Refresh", enabling users to reload the list to reflect the latest data entries.

#### 1.2 Data List

Below the header, a data grid displays contractor workforce records. The list includes the following column headers, each equipped with sort indicators (up/down arrows) for ascending and descending ordering:

* **Year**: The reporting year for the contractor workforce data.
* **Month**: The specific month during which the contractor data was recorded.
* **Company Name**: The name of the mining company associated with the contractor record.
* **Department**: The specific department or division within the mining company to which the contractor data pertains.
* **Expatriates Female**: The count of female expatriate contractors in the specified department during the reporting period.
* **Expatriates Male**: The count of male expatriate contractors in the specified department during the reporting period.
* **Ghanaian Employees Female**: The count of female Ghanaian contractors in the specified department during the reporting period.
* **Ghanaian Employees Male**: The count of male Ghanaian contractors in the specified department during the reporting period.
* **Skilled Labour**: The count of skilled labour contractors engaged by the mining company during the reporting period.
* **Unskilled Labour**: The count of unskilled labour contractors engaged by the mining company during the reporting period.

#### 1.3 Empty State

When no contractor records exist in the system, the data grid displays an empty state. Centered within the list area is a document inbox icon accompanied by the text **"No data"** in a light gray font. This indicates that no contractor data has been submitted or recorded for the current view.

***

### 2. Data Source

The information presented in the Contractors module is sourced from the **HR Statistics** upload section under Data Upload. Contractor statistics files uploaded through that module are processed and displayed here, providing a consolidated and analytical view of mining company contractor workforce composition across reporting periods.
