# ISO 27001:2022 Supplier Cybersecurity Self-Assessment

This repository provides an offline self-assessment package that procurement and security teams can send to suppliers to gauge their alignment to ISO/IEC 27001:2022 controls. The centerpiece is a single HTML form that captures supplier information, 39 control maturity responses, and an automatically calculated score without requiring any server-side components.

## Contents

- `supplier-cybersecurity-assessment.html` – Standalone browser form that suppliers complete, save locally, and return. All answers, progress indicators, and scores persist directly within the saved HTML.
- `how_to.md` – Internal playbook for the company running the program: covers preparation, distribution, intake, and retention of supplier submissions.
- `supplier_instructions-english.md` / `...-turkish.md` / `...-italian.md` / `...-spanish.md` – Ready-to-send guidance for suppliers explaining how to open, complete, save, and submit the assessment in each language.
- `README_DE.md`, `README_ES.md`, `README_FR.md` – High-level product overviews in German, Spanish, and French for teams that need localized summaries.
- `USER_GUIDE.md` – Legacy quick reference for suppliers in English (kept for continuity; superseded by the targeted instruction files above).

## Usage Overview

1. Program owner reviews `how_to.md`, selects the appropriate supplier instruction file, and emails both alongside `supplier-cybersecurity-assessment.html`.
2. Supplier opens the HTML locally, completes required company fields plus as many controls as possible, then clicks **Save Assessment to Disk**.
3. Supplier emails the newly downloaded `security_assessment-<supplier>-<YYYY-MM-DD>.html` file back to the requesting team.
4. Receiving team archives the returned HTML, reviews the embedded score and responses, and follows up on any gaps.

For versioning, consult the metadata at the bottom of each document. Update the instructions and questionnaire together whenever your control expectations change.*** End Patch
