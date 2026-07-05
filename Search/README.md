# Search Evidence Workspace

Project: Cosmetic Packaging Lightweighting Report

Purpose: Store source-backed evidence for non-patent research used in the report. Patent searches will be handled separately.

Structure:
- `Search/00_Master_Search_Plan.csv` lists the 20 research workstreams.
- Each search focus has its own subfolder.
- Each subfolder contains `evidence.csv`, an Excel-compatible evidence file with exactly four columns:
  1. Source code
  2. Summary of what was found
  3. Detailed description of what was found
  4. Source name

Working rule:
- Treat `Source code` as the unique evidence ID, e.g., `S01-001`.
- Put the source title and URL together in `Source name` so the final report remains traceable.
- Do not add patent results in these 20 folders; patent evidence will be captured separately.
