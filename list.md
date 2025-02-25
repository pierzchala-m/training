---
id: '1gSYi6ezNmuUNq37GzIKqK2EDVvDd2yFmW-83x1HPwKA'
title: 'list'
date: '2025-02-07T17:52:27.044Z'
version: 7
lastAuthor: 'mpierzchala'
mimeType: 'text/x-markdown'
links:
  - 'https://www.ietf.org/rfc/rfc4180.txt'
source: 'https://drive.google.com/open?id=1gSYi6ezNmuUNq37GzIKqK2EDVvDd2yFmW-83x1HPwKA'
wikigdrive: 'ba8923eb9d87ece97cc4deddda96f7dd47d67a15'
---
Data Migration follows the steps of Extraction, Transformation, and Loading, commonly referred to as ETL. The ETL strategy for this project is outlined in this section.

1. Extraction: The customer is responsible for delivering the following data:
    1. If applicable, legacy database backup(s) shall be exported and delivered to Enterprise Health for transformation and loading. New database exports shall be required for each cycle, plus dress rehearsal, plus final cutover.
    2. Decrypted scanned documents shall be packaged and delivered to EH.  One initial delivery (Delta) and additional documents for Dress Rehearsal and Go Live
    3. Excel or CSV reports
        1. Shall be collected as mutually agreed and discussed from one or more sources such as, but not limited to:
            1. Report exports from legacy systems
            2. Spreadsheets used for data tracking (e.g., GDrive Sheets, MS Teams, OneDrive)
            3. Spreadsheets collected from supervisors tracking HS memberships
        2. CSV files must conform to [RFC 4180](https://www.ietf.org/rfc/rfc4180.txt). The delimiter may be any single ascii character. Special characters must be escaped properly, and fields with newlines must be quoted.
