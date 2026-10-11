---
name: literature-add
description: Add a new paper to the user's literature library from a PDF file, DOI, arXiv ID, or paper URL. Use when the user wants to save, import, or ingest a paper into their library. Not for searching papers already in the library (use literature-search) or for setup and cleanup (use literature-manage).
---

# Add a paper

<!-- Preconditions: call literature-tools get_library first. If initialized is false,
     stop and point the user to the literature-manage skill to set up the library.
     Library layout and key format come from the literature-tools server instructions. -->

<!-- Ingest procedure: PDF → identify DOI/arXiv → literature-tools fetch_metadata → key →
     papers/<key>/ (paper.pdf, notes.md) via mkdir/cp → literature-tools convert_pdf → update index.md.
     Fallback when literature-tools isn't available. -->
