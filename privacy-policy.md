# Privacy Policy: Inventory Manager for Upland

Last updated: 11 November 2026
Developer: Achini Metaventures (Charles_FR)
Support: Discord server https://discord.gg/fVH2jnH9c7 or AchiniMetaventures@gmail.com

Inventory Manager for Upland ("the extension") is a Chrome extension that helps Upland players manage their showrooms, prices, stock and listings. This project is independent and not affiliated with Uplandme, Inc.

## Summary

- Everything the extension reads or saves stays in your browser.
- The developer receives nothing: no account, no analytics, no tracking, no remote logging.
- Nothing is sold, shared or used for advertising.

## What the extension accesses

When you use the extension on https://play.upland.me, it accesses:

1. Your in-game username, shown in the game page.
2. Your own inventory (structure ornaments, map assets, vehicles, seeds), your properties (addresses, cities), your showrooms, nurseries and factories, and their current listings and production queues. This information is read from Upland's own service (https://api.prod.upland.me) or from the game page.
3. Your session token. The game keeps it in the page session. The extension reads it only to call Upland's service on your behalf, the same way the game does. It is kept in memory, never saved by the extension and never sent anywhere except to Upland's service.
4. The prices, targets, tags, themes and options you type into the extension.

## Where the data is stored

All of this is saved locally in your browser with chrome.storage.local. It is not sent to the developer or to any third party. You can export it to a file (Settings, General, Backup) and import it again. You can erase it at any time by removing the extension, or from the browser's extension settings.

## Network requests

The extension makes only these requests:

- To https://api.prod.upland.me (Upland): to read your inventory, showrooms, factories and properties, and, when you click the corresponding button, to send a production request to one of your factories. Listings and delistings are made by operating the Upland page you have open, after you confirm a plan in the panel.
- To https://raw.githubusercontent.com (GitHub, public repository AchiniMetaventures/upland-trove-data): to read one small public file (inventory-manager/info.json) about every 12 hours, which may contain a short news message and a link. No data about you is sent. Like any web request, GitHub can see your IP address according to its own policy. The file contains text only; it is never run as code, and links must use https.

The extension does not use analytics, advertising, cookies of its own, or remote code.

## Sharing

The extension does not sell, rent or share your data. The only file that leaves your browser is one you choose to export yourself (backup, Excel price list, support snapshot), and you decide whom to send it to.

## Permissions

- storage and unlimitedStorage: save your settings, catalog and scans locally.
- sidePanel: show the extension in Chrome's side panel on Upland tabs.
- tabs and scripting: find your open play.upland.me tabs, enable the panel on them, open or focus the settings page, and re-attach the page script to a tab opened before the extension was installed or updated.
- Access to https://play.upland.me and https://api.prod.upland.me: read the game page and Upland's service as described above.

## Children

The extension is a tool for Upland players and is not directed at children under 13.

## Changes

If this policy changes, the date above is updated and the new text is published at the same address.

## Contact

Questions: Discord server https://discord.gg/fVH2jnH9c7 or AchiniMetaventures@gmail.com.
