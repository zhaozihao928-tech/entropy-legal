# Privacy Policy

**Last updated: 2026-10-26**

This policy applies to **Finished**, a private command-line tool operated by the
owner of the YouTube channel "熵减日记" (the "Operator").

## 1. Who this covers

Finished is a single-user tool. It is not distributed, not published, and has no
users other than the Operator. There is no public sign-up, no account system, and
no third-party access.

## 2. What data the tool handles

The only data Finished touches is:

- **The Operator's own Google account credentials** — specifically an OAuth 2.0
  access token and refresh token issued by Google when the Operator authorises
  the tool. These are stored as a file on the Operator's own device, readable only
  by the Operator's user account (file mode 600).
- **Video files, thumbnail images and subtitle files** that the Operator
  explicitly placed in a local folder for publishing.
- **A local publishing log** recording which file was uploaded, the resulting
  video ID, and the timestamp — so the same file is not uploaded twice.

## 3. What the tool does NOT do

- It does not collect, read or store any data belonging to any other person.
- It does not use cookies, analytics, tracking pixels or advertising identifiers.
- It does not collect viewer data, viewing history or any YouTube Analytics
  report.
- It does not sell, rent, share or transfer any data to any third party.
- It does not store data on any server. All data stays on the Operator's device.

## 4. How data is transmitted

Data is sent only to Google's own API endpoints over HTTPS
(`www.googleapis.com`, `oauth2.googleapis.com`, `accounts.google.com`), and only
for the purpose of uploading the Operator's own content to the Operator's own
channel. No other destination receives any data.

## 5. Data Deletion

**How to delete the data this tool holds**

The tool stores exactly two things on the Operator's device: an OAuth token file
and a local publishing log. Both are deleted as follows.

| Data | How to delete it | How long it takes |
|---|---|---|
| OAuth access token and refresh token | Delete the token file on the device, **and** revoke the grant at https://myaccount.google.com/permissions | Revocation is immediate |
| Local publishing log (file names, video IDs, timestamps) | Delete the log file on the device | Immediate |
| Uploaded videos, thumbnails and captions | Deleted in YouTube Studio, or via the YouTube API | Within 24 hours of deletion, per YouTube's own policy |

**Revoking access**

Visit https://myaccount.google.com/permissions, find the entry named
"Finished", and click "Remove access". The stored token stops working
immediately. The tool cannot access YouTube again until the Operator authorises
it again.

**What is NOT stored**

The tool keeps no server, no cloud database and no backup. It does not store
viewer data, comments, analytics or any information about anyone other than the
Operator. There is therefore nothing to request, export or delete on a server —
deleting the two local files removes everything.

**Contact for deletion requests**

Because the tool has a single user, any deletion request can only come from that
user. For any question: zhaozihao928@gmail.com

## 6. YouTube API Services

Finished uses YouTube API Services. By using this tool the Operator agrees to be
bound by the
[YouTube Terms of Service](https://www.youtube.com/t/terms).

Google's privacy practices are described at
https://policies.google.com/privacy.

The Operator's use of the tool is also subject to Google's
[Privacy Policy](https://policies.google.com/privacy).

## 7. Children

The tool is not directed at children and handles no data from anyone other than
its single adult Operator.

## 8. Changes

If this policy changes, the "Last updated" date above changes and the revised
text replaces this page.

## 9. Contact

For any question about this policy: zhaozihao928@gmail.com
