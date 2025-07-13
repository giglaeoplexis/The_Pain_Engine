# Rule File: Diary and Summary File Standard

## Purpose
To ensure consistent and comprehensive session documentation, all records of daily work, creative reflection, file changes, and session goals will be merged into a single file per session. This file serves as both a technical manifest and a narrative diary, supporting both reproducibility and creative process tracking.

---

## Directory Structure

- All merged diary/summary files are stored in a dedicated directory within the repository (e.g., `/diaries/`).
- A separate `staging/` directory exists outside the main repository directories for temporary holding of downloaded, in-progress, or unreviewed files. Only files ready for permanent record should be moved into `/diaries/` or other versioned folders.

**Example Directory Layout:**
```
ThePainEngine/
├─ diaries/              # Final, version-controlled diary/summary files
│    └─ daily_diary_YYYY-MM-DD_HHMM_VersionX.md
├─ rules/                # Rule and standard files (like this one)
│    └─ diary_and_summary_file_standard.md
├─ staging/              # Temporary, non-versioned working area (outside the repo if desired)
│    └─ (downloaded/generated/in-progress files)
```

---

## File Naming Convention

- **Format:** `daily_diary_YYYY-MM-DD_HHMM_VersionX.md`
- **Example:** `daily_diary_2025-07-12_1655_Version1.md`
- **Rationale:** Timestamp and version ensure uniqueness and clear chronological order, supporting multiple entries per day.

---

## File Structure Template

Copy and use the following template for each new session:

````markdown name=diaries/daily_diary_YYYY-MM-DD_HHMM_VersionX.md
# Daily Diary & Session Summary — YYYY-MM-DD HH:MM (UTC)

## Manifest Section

- **Participants:**  
  - User: <yourusername>
  - AI Collaborator: GitHub Copilot

- **Session Start Time:** YYYY-MM-DD HH:MM (UTC)
- **Session End Time:** YYYY-MM-DD HH:MM (UTC)

- **Goals for This Session:**
  - (list goals here)

- **Files Generated/Modified:**
  - (list files here)

- **Tasks Completed:**
  - (list completed tasks)

- **Tasks to Carry Over:**
  - (list unfinished tasks or next steps)

- **Key Decisions:**
  - (summarize major decisions made this session)

---

## Diary Section

- **Session Narrative/Reflection:**
  - (write a narrative log, thoughts, breakthroughs, challenges, mood, etc.)

- **Additional Notes:**
  - (anything else to remember or reflect on)

---

## References

- (link to related files, rules, or previous diary entries as needed)

---

*End of entry.*