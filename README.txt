BJMP NATIONWIDE DOCUMENT AUTOMATION — VERSION 1.0
Sipocot District Jail initial deployment prototype

NEW IN VERSION 1.0
- Multiple JPG/PNG photo upload for documentation.
- EXIF DateTimeOriginal/CreateDate/ModifyDate extraction when available.
- Chronological photo sorting.
- Earliest readable photo timestamp is suggested as activity start.
- User can review/correct the confirmed activity start.
- Editable photo captions.
- Live document preview and browser Print / Save as PDF.
- DOCX generation with photo evidence and captions.

IMPORTANT LIMITATIONS
- This is a local browser prototype. It does not provide central multi-unit synchronization, secure user accounts, server-side access controls, or approved records retention.
- Photo timestamps are metadata and are not proof by themselves that an activity started at that time. Verify before signing.
- EXIF may be absent, stripped, or incorrect. Manual review is required.
- The generated document is a draft framework, not a verified reproduction of every current BJMP MC annex. Check current controlled BJMP templates, applicable MCs, official letterhead, QMS procedures, signatory authority, and paper size before official use.
- ISO 9001 is a quality management system standard; it does not prescribe a universal BJMP document layout.
- Do not upload confidential PDL, personnel, security, or operational records to this public GitHub Pages prototype.

HOW TO DEPLOY
Upload/replace index.html and README.txt in the repository root. Keep the existing assets/ folder, manifest.json, and sw.js. Commit changes, wait for GitHub Pages deployment, then reload the site.
