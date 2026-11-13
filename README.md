# PDF upload size limits on official portals

A small, sourced list of the file size limits that government and hiring portals put on PDF uploads. Every row links to the official page it came from and shows the date it was last checked.

If a limit has changed, please open an issue or a pull request with the new source link.

| Portal | What you upload | Limit | Formats | Official source | Last checked |
|---|---|---|---|---|---|
| USCIS online filing (US) | Evidence attached to an online form | 12 MB per file | PDF, JPG, JPEG | [uscis.gov: Tips for filing forms online](https://www.uscis.gov/file-online/tips-for-filing-forms-online) | 2026-11-13 |
| IRS Documentation Upload Tool (US) | Documents in reply to an IRS notice | 15 MB per file, up to 40 files | PDF, JPEG, PNG | [irs.gov: IRS expands secure digital correspondence (FS-2023-05)](https://www.irs.gov/newsroom/irs-expands-secure-digital-correspondence-for-taxpayers) | 2026-11-13 |
| IRCC secure account (Canada) | Supporting documents | 4 MB per file (most IRCC accounts) | see source | [IRCC Help Centre, answer 1123](https://ircc.canada.ca/english/helpcentre/answer.asp?qnum=1123&top=23) | 2026-11-13 |
| Protean PAN application (India) | ID, address and date of birth proofs | 300 KB per page, PDF | PDF | [Protean: PAN documents scanning and uploading](https://www.proteantech.in/articles/pan-card-documents-scanning-uploading-method/) | 2026-11-13 |
| Greenhouse job applications | Resume (for automatic parsing) | Parsing fails above 2.5 MB | see source | [Greenhouse support article 200989175](https://support.greenhouse.io/hc/en-us/articles/200989175) | 2026-11-13 |

The same data is in [limits.csv](limits.csv).

## Getting a file under the limit

- Scans and phone photos are usually the problem. Scanning at 150 to 200 DPI in grayscale is often enough to stay readable and small.
- Keep text documents (forms, resumes) as text PDFs. Turning pages into images makes them bigger and stops portals and applicant tracking systems from reading the text.
- If one file holds several documents, split it and upload the parts separately where the portal allows more than one file.

Step-by-step guides with test results for some of these portals:

- [Compress a PDF for USCIS online filing (12 MB per file)](https://www.pdf-i-love.com/guides/compress-pdf-for-uscis/)
- [Compress a PDF under 4 MB for IRCC uploads](https://www.pdf-i-love.com/guides/compress-pdf-for-ircc/)
- [PAN card PDF size: get documents under 300 KB](https://www.pdf-i-love.com/guides/pan-card-pdf-size/)

## About

Maintained by the team behind [PDF-I-LOVE](https://www.pdf-i-love.com/), a set of free PDF tools. This list is independent of the portals named above and is not legal or immigration advice. Always check the limit shown on the upload page itself, because portals change their rules.

Data is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
