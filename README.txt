BJMP NATIONWIDE DOCUMENT AUTOMATION — VERSION 0.8
National Correspondence Engine (Prototype)

DOCUMENT BASIS
This prototype maps document structures to the publicly accessible BJMP Communications Policy:
BJMP-CDS-MC-133, "Guidelines, Formats and Standards of BJMP Correspondences",
effective 21 February 2022, published copy hosted by BJMP Regional Office I.

Implemented annex-based draft structures:
- Annex B: Memorandum Format for General Purposes
- Annex C: Memorandum Format for Requests
- Annex D: After Activity Report (AAR) Format
- Annex E: Formal/Business Letter Format
- Annex H: Spot Report Format
- Annex H1: Progress Report Format
- Annex I2: Routing Slip for Jail Units
- Annex J: Notice of Meeting Format
- Annex K: Minutes of the Meeting Format
- Annex M: Event Profile Sheet Format

Formatting applied to DOCX drafts from MC-133 general rules:
- A4 paper
- 1-inch margins
- Tahoma 12
- Black text
- Single line spacing and paragraph spacing

IMPORTANT COMPLIANCE NOTES
1. The MC-133 source PDF is a 2022 copy. Before official issuance, confirm whether BJMP NHQ has issued amendments, superseding policies, updated annexes, or separate mandatory forms.
2. Annex N (Common Jail Issuances) is not fully reproduced as an automated controlled template in this prototype. The "Other / Common Jail Issuance" option produces a marked working draft only. Do not use it as an official General Order or Special Order without the current approved form.
3. This is NOT an ISO-certified or BJMP-approved system. ISO 9001:2026 is the current published edition as of November 2026; implementation and certification applicability must be determined by the agency's QMS authority. This front-end prototype does not implement a validated QMS, controlled server records, audit-grade e-signatures, or retention controls.
4. All generated documents are DRAFTS. The authorized Warden/signatory must review and approve them. The software does not confer signing authority, auto-approve documents, or guarantee correct routing.
5. The app runs in the browser and relies on the docx JavaScript library from a CDN. An internet connection is needed for DOCX generation.
6. Do not enter confidential PDL, personnel, intelligence, security, or operational information in this public GitHub Pages prototype.
7. Data remains in local browser storage. No secure authentication, server-side authorization, encrypted central database, or cross-device synchronization is included.

HOW TO TEST
1. Open index.html from GitHub Pages or locally in a browser with internet.
2. Open Document Automation.
3. Select an Annex-based template.
4. Complete the fields relevant to that document.
5. Generate Word document (.docx).
6. Review the file in Microsoft Word/LibreOffice and verify all details before use.

SOURCE
BJMP Regional Office I, Memorandum Circular PDF:
https://r1.bjmp.gov.ph/wp-content/uploads/2023/03/02.21.2022_MC_ON_COMMUNICATIONS_POLICY.pdf

ISO CURRENT EDITION REFERENCE
ISO 9001:2026, published 16 September 2026:
https://www.iso.org/standard/9001

This software is an independent prototype and is not an official BJMP product.
