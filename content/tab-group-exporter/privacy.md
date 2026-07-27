---
title: "Privacy Policy — Tab Group Exporter"
date: 2026-07-27T00:00:00+08:00
draft: false
url: "/tab-group-exporter/privacy/"
description: "Privacy policy for the Tab Group Exporter Chrome extension."
ShowReadingTime: false
ShowShareButtons: false
ShowPostNavLinks: false
ShowBreadCrumbs: false
---

_Last updated: July 27, 2026_

Tab Group Exporter is designed to work entirely on your device.

## Data the extension accesses

When you open the extension, it reads the titles, URLs, tab-group names, tab-group colors, and related tab state from the current Chrome window. This access is necessary to show the export preview and create the HTML, JSON, or CSV file you request.

When you choose an export file to import, the extension reads that selected file locally to build an import preview. It then opens only the items you select.

If you choose **Save to bookmarks**, Chrome asks for optional bookmark access. After you grant it, the extension creates a new dated folder in Other bookmarks and writes the current tab groups into that folder. The extension does not search, read, reorganize, or delete your existing bookmarks. If creation fails partway through, it may remove only the new folder created by that attempt so that no incomplete export remains.

## Data collection and sharing

Tab Group Exporter does not collect, transmit, sell, or share personal data or browsing activity. It has no server, analytics, advertising, account system, or remote code.

Export files are created locally and saved through your browser's normal download process. The extension does not upload or retain a copy of them.

## Data storage

The extension does not maintain a database of your tabs, browsing activity, or bookmarks. Any HTML, JSON, or CSV file remains under your control in the location chosen by your browser. Bookmark exports remain in your Chrome bookmark storage under your control.

## Permissions

- `tabs`: used to read the URL and title of tabs in the current window and to open selected tabs during import.
- `tabGroups`: used to read, create, and update Chrome tab groups during export and import.
- Optional `bookmarks`: requested only when you choose **Save to bookmarks**. It is used to create a new folder and bookmarks for the current tab groups, and to remove only that newly created folder if the operation fails.

These permissions are used only for the extension's single purpose: moving the tab groups in the current Chrome window into portable files or Chrome bookmarks, and importing supported files back into Chrome.

## Limited Use

The use of information received from Chrome APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Contact

For privacy questions or bug reports, contact [exploreryer@protonmail.com](mailto:exploreryer@protonmail.com).
