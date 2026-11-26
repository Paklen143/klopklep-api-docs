# Privacy Policy — KlopKlep Publishing Pipeline

Last updated: 26 November 2026

This policy describes how the KlopKlep publishing pipeline ("the tool") handles data when publishing videos to the YouTube channels @KlopKlep and @klopklepclips.

## Who operates the tool
The tool is operated privately by Muhammad Fadhlan Nur Aulia (muhammadfadhlannuraulia@gmail.com), the owner of the YouTube channels listed above. It is not offered as a public service, has no user accounts, and is not distributed to third parties.

## What data the tool accesses
The tool uses YouTube Data API v3 with the owner's own OAuth authorization to:
- upload video files the owner has produced to the owner's own channels (`videos.insert`);
- read the owner's own channel information and upload list (`channels.list`, `playlistItems.list`) to avoid uploading the same video twice.

## What data the tool stores
- The video files, titles, descriptions and tags produced locally by the owner.
- OAuth credentials for the owner's own channels, stored locally on the owner's own computer with file permissions restricted to that user.
- A local log of uploads (file name, checksum, video ID, timestamp) used solely to prevent duplicate uploads.

No YouTube user data, viewer data, comments, or third-party channel data is collected, stored, or analysed.

## Data sharing
No data is sold, rented, transferred, or shared with third parties. No YouTube API data is displayed publicly or used for advertising. The tool does not run advertising and has no advertising partners.

## Data retention
Upload logs and checksums are kept on the owner's own device for as long as needed to prevent duplicate publishing. OAuth tokens can be revoked at any time by the owner from their Google Account permissions page.

## Google user data
The tool's use of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements. YouTube data obtained through the API is used only for the purposes described above.

## Children
The tool is not directed to children and does not knowingly collect data from children.

## Changes
Any change to this policy will be published on this page with an updated date.

## Contact
Muhammad Fadhlan Nur Aulia — muhammadfadhlannuraulia@gmail.com
