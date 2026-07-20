# Energy

***

## Energy Module — User Interface Documentation

### Overview

This document describes the user interface of the **Energy** module within The Ghana Chamber of Mines web portal. The module enables authorized users (managers) to browse, search, and analyze energy consumption data submitted by their respective mining companies. The data displayed in this module originates from the **Technical Statistics** section under Data Upload, where energy statistics are first captured and submitted.

***

### 1. Energy List (View Page)

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-20 145546.png" alt=""><figcaption><p>Energy List</p></figcaption></figure>

#### 1.1 Page Header

At the top of the content area, the page title **"Energy List"** is displayed in bold, preceded by a back arrow icon (`←`) for navigation to the parent page. To the right of the title, the following controls are available:

* **Search Field**: A text input box with a light gray placeholder text "search", allowing users to filter the list of energy consumption records by relevant keywords.
* **Refresh Button**: A circular refresh icon accompanied by the label "Refresh", enabling users to reload the list to reflect the latest data entries.
* **Filter by Company Dropdown**: A dropdown selection field labeled "Filter by Company" with a downward-facing chevron icon, allowing users to narrow the displayed records to a specific mining company.

#### 1.2 Data List

Below the header, a data grid displays energy consumption records. The list includes the following column headers, each equipped with sort indicators (up/down arrows) for ascending and descending ordering:

* **Company Account**: Identifies the mining company associated with the energy consumption record.
* **Year**: The reporting year for the energy consumption data.
* **Month**: The specific month during which the energy data was recorded.
* **Quarter**: The fiscal quarter corresponding to the reporting period.
* **Electrical Power Consumed**: The total amount of electrical power consumed by the mining operation during the reporting period.
* **Volume Of Diesel Consumed (L)**: The total volume of diesel fuel consumed by the mining operation during the reporting period, measured in liters.

#### 1.3 Empty State

When no energy consumption records exist in the system, the data grid displays an empty state. Centered within the list area is a document inbox icon accompanied by the text **"No data"** in a light gray font. This indicates that no energy consumption data has been submitted or recorded for the current view.

***

### 2. Data Source

The information presented in the Energy module is sourced from the **Technical Statistics** upload section under Data Upload. Energy statistics files uploaded through that module are processed and displayed here, providing a consolidated and analytical view of mining energy consumption metrics across reporting periods.
