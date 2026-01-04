# 01 — EVIDENCE RECORD (Canonical)

This folder is the **canonical evidential record** for *Zahmoul v Secretary of State for Justice & HMCTS* (Judicial Review: **AC-2025-LON-004293**).

It is designed for **transparency, scrutiny, and forensic auditability**.  
All evidence is organised so a reviewer can distinguish between:
1) **primary source materials** (raw inputs),  
2) **evidential work products** (derived from sources, with limited analysis), and  
3) **formal exhibit bundles / indexes** (structured presentation of evidence).

> **Court outputs** (orders/judgments/directions) are stored separately in `02_COURT_DECISIONS_AND_ORDERS`.  
> **Pleadings and advocacy** (claim form, submissions, skeletons, annexes) are stored separately in `03_PLEADINGS_AND_SEALED_APPLICATIONS`.

---

## Evidence map (what lives where)

### A. Primary source evidence (raw inputs)
**Purpose:** documents that exist independently of any analysis or advocacy (e.g., medical records, contemporaneous correspondence, source records, transcripts, original files).

- Store these in:  
  `01_EVIDENCE_RECORD/1_RAW_PRIMARY_EVIDENCE/`

(If a document is a “source”, it belongs here.)

---

### B. Evidential work products (derived from sources)
**Purpose:** materials created to transmit, organise, or explain evidence (may contain limited analysis), while preserving provenance and traceability.

This repository currently contains:

- `01_EVIDENCE_RECORD/2_EVIDENTIAL_WORK_PRODUCTS/CRIMINAL_REFERRALS/`  
  Contains the UK-nexus criminal referral pack and cross-reference note. :contentReference[oaicite:1]{index=1}

- `01_EVIDENCE_RECORD/2_EVIDENTIAL_WORK_PRODUCTS/IMERMAN_EVIDENCE/`  
  Contains evidential materials relating to Imerman handling/custody and associated public-law duties notes. :contentReference[oaicite:2]{index=2}

- `01_EVIDENCE_RECORD/2_EVIDENTIAL_WORK_PRODUCTS/IMERMAN_EXHIBITS/`  
  Contains the Imerman exhibit set and master exhibit materials used to present and track the Imerman evidential record. :contentReference[oaicite:3]{index=3}

Top-level index of this tier:  
`01_EVIDENCE_RECORD/2_EVIDENTIAL_WORK_PRODUCTS/` :contentReference[oaicite:4]{index=4}

---

### C. Formal exhibit bundles and indexes (structured presentation)
**Purpose:** assembled bundles prepared for external scrutiny (court/counsel/public versions), including any redacted public bundles and exhibit compilations.

Store these in:  
`01_EVIDENCE_RECORD/3_FORMAL_EXHIBIT_BUNDLES_AND_INDEXES/`

Examples include:
- public/redacted exhibit bundles prepared for counsel / external scrutiny,
- compiled exhibit bundles filed or prepared for filing,
- bundle indexes and bundle maps.

---

## Naming, provenance, and integrity rules

1. **Do not edit primary evidence files once uploaded.**  
   Any commentary or analysis belongs in work products or separate notes.

2. **Keep original filenames where possible.**  
   If renaming is unavoidable (e.g., “scan123.pdf”), use:
   `YYYY-MM-DD_Source_Type_ShortDescription.ext`

3. **Redaction transparency:**  
   If a file is redacted, mark it clearly in the filename (e.g., `_REDACTED`, `_PublicVersion`).  
   Never overwrite an unredacted original with a redacted version.

4. **One canonical location per item.**  
   Avoid duplicates. If something must be referenced from elsewhere, reference it by path.

---

## Purpose of this folder (why it matters)

This folder provides the **neutral evidential baseline** against which:
- the court’s procedural history (`02_...`) and  
- the parties’ pleadings and advocacy (`03_...`)  
can be assessed for accuracy, completeness, and fairness.

It is maintained to support:
- judicial review scrutiny,
- parliamentary and journalistic oversight,
- and an auditable public record.





