---
title: "Privacy Policy — Tab Group Exporter"
date: 2026-07-29T00:00:00+08:00
draft: false
url: "/tab-group-exporter/privacy/"
description: "Privacy policy for the Tab Group Exporter Chrome extension."
ShowReadingTime: false
ShowShareButtons: false
ShowPostNavLinks: false
ShowBreadCrumbs: false
---

_Last updated: July 29, 2026_

Tab Group Exporter is designed to work entirely on your device.

## Data the extension accesses

When you open the extension, it reads the titles, URLs, tab-group names, tab-group colors, and related tab state from the current Chrome window. This access is necessary to show the selectable export list and create the HTML, JSON, or CSV file you request.

When you choose an export file to import, the extension reads that selected file locally to build an import preview. It then opens only the items you select.

If you choose **Save to bookmarks**, Chrome asks for optional bookmark access. The default destination is **Other bookmarks › Tab Groups**. If you open the destination selector, the extension reads the bookmark folder tree locally so it can show the available folders. It does not display or inspect bookmark URLs while choosing a destination.

After you choose a destination, the extension creates or reuses a **Tab Groups** folder inside it. It reads that managed folder and its direct group folders to find matching folders and URLs that are already saved, then adds the selected bookmarks. It does not reorganize unrelated bookmarks.

Before saving, you can choose **Keep tabs open** or **Close selected tabs**. Tabs are closed only after the bookmark operation succeeds, and only the selected, supported web tabs are affected. If bookmark creation fails, no tabs are closed. If a write fails partway through, the extension attempts to remove only the nodes created by that incomplete attempt.

## Data collection and sharing

Tab Group Exporter does not collect, transmit, sell, or share personal data or browsing activity. It has no server, analytics, advertising, account system, or remote code.

Export files are created locally and saved through your browser's normal download process. The extension does not upload or retain a copy of them.

## Data storage

The extension does not maintain its own database of your tabs, browsing activity, or bookmarks. Any HTML, JSON, or CSV file remains under your control in the location chosen by your browser. Bookmark exports remain in your Chrome bookmark storage under your control.

## Permissions

- `tabs`: used to read the URL and title of tabs in the current window, open selected tabs during import, and close selected tabs only when you explicitly choose **Close selected tabs** after a bookmark save.
- `tabGroups`: used to read group names, colors, and collapsed state during export, and to create or update Chrome tab groups during import.
- Optional `bookmarks`: requested only when you use **Save to bookmarks** or open the destination selector. It is used to show bookmark folders, create or reuse the managed **Tab Groups** folder in the chosen destination, read its direct contents for matching folders and duplicate URLs, add selected bookmarks, and remove only nodes created by an incomplete attempt where possible.

These permissions are used only for the extension's single purpose: moving selected tab groups in the current Chrome window into portable files or Chrome bookmarks, optionally closing successfully saved tabs, and importing supported files back into Chrome.

## Limited Use

The use of information received from Chrome APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Contact

For privacy questions or bug reports, contact [exploreryer@protonmail.com](mailto:exploreryer@protonmail.com).
