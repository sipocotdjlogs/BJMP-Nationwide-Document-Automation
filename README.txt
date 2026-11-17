BJMP NATIONWIDE DOCUMENT AUTOMATION — VERSION 1.2
Sipocot District Jail initial deployment prototype

WHAT'S INCLUDED
- Expanded AAR input workspace based on the uploaded dines.docx content sequence:
  memorandum routing (FOR / THRU / SUBJECT / DATE), multiple references,
  mission/purpose, place/s covered, date covered and activity times,
  repeatable participants, repeatable narrative paragraphs, issues,
  concerns, recommendations, supporting attachments, and signatory details.
- Two selectable AAR content layouts:
  1) Sipocot District Jail — November 17, 2026 sample
  2) BJMP Regional Office V / Sipocot — November 16, 2026 dines.docx sample
- Uses the existing Sipocot unit mark and BJMP seal assets in the AAR preview and generated DOCX.
- Multiple JPG/PNG upload, EXIF capture-time reading where metadata exists,
  chronological sorting, captions, earliest valid photo timestamp suggestion,
  live preview, browser print / Save as PDF, and DOCX export.
- Repeatable add/remove controls for references, participants, and narrative paragraphs.

IMPORTANT
- This is a browser-side prototype. It is not connected to a secure central database.
- The generated DOCX is assembled from the entered content and layout rules; it does not preserve every underlying Word XML style, exact paragraph metric, original header/footer, or page break from the uploaded master DOCX byte-for-byte.
- Confirm all content, official logos, current controlled BJMP MC templates, paper size, signatory authority, and QMS procedures before official release.
- EXIF timestamps can be absent or incorrect; the earliest timestamp is only a suggestion and must be verified.
- Do not upload confidential PDL, personnel, security, or operational records to the public GitHub Pages prototype.

DEPLOYMENT
Upload/replace index.html and README.txt in the repository root.
Keep the existing assets/ folder, manifest.json, and sw.js.
Commit changes and wait for GitHub Pages deployment, then reload the site.
