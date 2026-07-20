# Meetings

## Committee Meetings Module — User Interface Documentation

### Overview

The Committee Meetings module provides a centralized interface for managing and reviewing organizational meetings. The layout is divided into a persistent navigation sidebar and a dynamic content area that adapts based on the selected view.

***

### 1. Meetings List View

<figure><img src="../../.gitbook/assets/Screenshot 2026-07-20 213257.png" alt=""><figcaption><p>Meeting List</p></figcaption></figure>

The left panel of the content area displays the **Meetings** list.

#### Search and Refresh Controls

* **Search Meetings...** — A text input field allowing users to filter the meetings list by keyword.
* **Refresh** — A circular button to reload the meetings list and retrieve the latest data.

#### Meeting Entry

When meetings exist, each entry displays:

* **Avatar** — A circular icon containing the first letter of the meeting name.
* **Meeting Name** — The title of the meeting (e.g., "JOIN NOW").
* **Location** — The venue where the meeting is scheduled (e.g., "Conference Room").
* **Status and Time** — The current state of the meeting (e.g., "upcoming") and the scheduled start time (e.g., "3:40 PM").
* **Committee Assignment** — The committees associated with the meeting (e.g., "None" or "All").
* **Date Badge** — A date indicator positioned on the right side of the entry (e.g., "Jul 9").

***

### 3. Meeting Detail View

Selecting a meeting from the list opens the **Meeting Detail** view in the right panel.

#### Navigation Controls

* **Back** — A button to return to the meetings list.
* **Pagination** — Navigation arrows and a counter (e.g., "1/1") to browse through multiple meeting records.
* **Timestamp** — The last updated or received time displayed in the upper-right corner (e.g., "12:00 AM, Jul 9").

#### Header Information

* **Meeting Name** — The full title of the meeting displayed prominently (e.g., "JOIN NOW").
* **Avatar and Location** — A circular avatar with the meeting name's initial, followed by the venue (e.g., "Conference Room").
* **Committee Scope** — The target audience for the meeting (e.g., "to Committees: All").

#### Body Content

The detail view presents a formal invitation structure containing the following fields:

* **Salutation** — Opening greeting (e.g., "Hi,").
* **Invitation Statement** — A formal message inviting the recipient to the meeting (e.g., "This is a formal invitation to the upcoming meeting, JOIN NOW.").
* **Date** — The scheduled date and time of the meeting (e.g., "09 Jul 2026 at 3:40 PM").
* **Venue** — The physical or virtual location of the meeting (e.g., "Conference Room").
* **Status** — The current meeting state displayed as a visual badge (e.g., "upcoming").
* **Meeting Link** — A clickable hyperlink to access the meeting or related resources (e.g., "http://localhost:3100/committeemeeting/create").
* **Closing Instructions** — Additional guidance for attendees (e.g., "Please review any attached documents prior to the meeting. Your timely attendance and participation are highly expected.").
