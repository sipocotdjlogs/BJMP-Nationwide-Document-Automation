BJMP NATIONWIDE DOCUMENT AUTOMATION — VERSION 1.1
Sipocot District Jail working prototype

FIXES / FEATURES
- Rebuilt from the clean v0.9 source so external scripts are correctly closed and loaded.
- One DOCX generator handler only (removed duplicated/broken v1.0 script blocks).
- Added two distinct AAR layouts based on the two user-provided AAR samples:
  1) Sipocot District Jail, November 17, 2026: centered Sipocot letterhead, MEMORANDUM, FOR, SUBJECT, DATE, and sections 1–7.
  2) BJMP Regional Office V / Sipocot, May 20, 2025: Regional Office V heading, SDJLOGISTIC, MEMORANDUM, FOR, THRU, SUBJECT, DATE, and the source's References, Mission/Purpose, Place/s Covered, Date Covered, Participants, Narrative, and Issues/Concerns/Recommendations sequence.
- Multiple JPG/PNG photo upload.
- EXIF DateTimeOriginal/CreateDate/ModifyDate reading when available.
- Photos sorted earliest to latest; earliest readable timestamp suggested as activity start.
- Manual review/correction of activity start and editable captions.
- Live preview and browser Print / Save as PDF.
- DOCX generation with selected AAR layout and photo documentation.

IMPORTANT
- The two layouts reproduce the structure of the uploaded examples, not a claim of official approval or full MC compliance.
- Confirm current controlled BJMP MC templates, correct approved letterhead/logo, QMS procedure, routing, signatories, and paper size before official use.
- EXIF timestamp may be absent, stripped, or inaccurate; it is not proof of the actual activity start. Verify before signing.
- This is a browser-side prototype. It does not provide secure centralized multi-unit synchronization, role-based server access, or official records retention.
- Do not upload confidential PDL, personnel, security, or operational records to a public GitHub Pages site.

DEPLOY
In the repository root, replace index.html and README.txt with these Version 1.1 files. Keep the existing assets/ folder, manifest.json, and sw.js. Commit the changes and wait for GitHub Pages deployment. Then reload the site (hard refresh or Incognito if cached).
