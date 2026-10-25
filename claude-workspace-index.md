# Claude Workspace Index

As of 2026-10-25 · Ramandeep Singh

This is the single map of every active Claude-related project: what it is, where its files actually live (if anywhere), and current status in one line. Each project's own CLAUDE.md or memory file holds the full detail — this page is for finding things, not for storing them twice.

## Projects

| Project | Where it lives | Status |
| --- | --- | --- |
| Decoding the ICU (ebook) | Dropbox: Claude Projects/icu-family-ebook/ (synced Mac + Windows) | Manuscript + cover done; next: publish to Amazon KDP |
| Clinic AI service | Dropbox: Claude Projects/clinic-ai-service/ (synced Mac + Windows) | Pre-build; no working demo yet |
| YouTube channel | Dropbox: Claude Projects/youtube-channel/ (synced Mac + Windows) | Planning; audience angle (investor vs. patient) undecided |
| Gardening app | Dropbox: Claude Projects/gardening-app/ (built in Lovable; synced Mac + Windows) | In build — class project |
| Wardrobe organiser app | Dropbox: Claude Projects/wardrobe-organiser-app/ (Lovable + Replit; synced Mac + Windows) | In build; on-device-vs-cloud storage conflict unresolved |
| Reading summarizer workflow | Dropbox: Claude Projects/reading-summarizer-workflow/ (synced Mac + Windows) | Prompt tested on 5 links; scaling to full automation |
| ramans-ai-journey (this GitHub repo) | Windows: C:\Users\Raman\Documents\ramans-ai-journey | Active repo; contains nurse-shift-scheduler tool (built, HTML app) — README's Tools section not yet updated to list it |
| Riley (Vapi voice agent) | Hosted (Vapi + Val Town); no local folder | Working; "send texts" feature still pending |
| Jarvis (desktop voice assistant) | Decommissioned 2026-10-08 | No files remain anywhere |
| voice-agent-mvp (3rd voice agent) | Dropbox: Claude Projects/voice-agent-mvp/ (synced Mac + Windows; canonical copy since 2026-10-14 migration) | MVP working; Phase 2 Tier 0 live. Old Windows-only backup at Documents\Claude Work\voice-agent-mvp\ not yet deleted — still has a live .env API key |
| Dropbox cleanup | Windows: D:\Dropbox, D:\DropboxBackup | Resolved; Dropbox Plus active; 2012–13 videos still single point of failure |
| Perioperative Risk & Drug Console | Claude.ai artifact only, no device file ([link](https://claude.ai/artifact/Bfnw3WAemtmNgfbEMJ2obV)) | Self-tested only, not used on real patients |
| OT conversion tracker | Dropbox: Claude Projects/ot-conversion-tracker/ | Stage 1; pipeline not yet validated with real hospital data |
| n8n automations (Google Sheets) | Not yet set up | Planning stage |
| Bill reminders | Google Calendar | Active: ADCB, DIB card + DIB EMI reminders |

## Known gaps

- Resolved 2026-10-23: the n8n memory duplicate was merged, and all six Mac-only project folders were migrated into Dropbox `Claude Projects/`. Dropbox is now the single standard location for every project, on every machine; Google Drive stays connected for Gmail/Calendar only, not file storage.
- Resolved 2026-10-24: the `voice-agent-mvp` "duplicate" was not actually a conflict — it was a documented 2026-10-14 migration to Dropbox that this index hadn't caught up on. Both machines' local CLAUDE.md files now record this.
- Resolved 2026-10-24: `mood-tracker` and `testing claude\dad-75.html` were mock-drill test files, confirmed by Ramandeep and deleted — not real projects, removed from this index.
- Resolved 2026-10-25: corrected the ramans-ai-journey status line above — the repo's README does not actually list nurse-shift-scheduler (its Tools section is still empty); the tool itself is real and present in the repo at `nurse-shift-scheduler/index.html`.
- Flagged 2026-10-25: an older memory note ("hospital_ai_dosing_tool", 2026-09-19, filed under a separate Claude.ai Project) describes a pitch for an AI dosing/crisis-management tool for ICU, Emergency and anaesthesia at Ramandeep's own hospital. Unclear whether this is the same idea as the tracked "Clinic AI service" row above or a separate, untracked item — Ramandeep to say which.
- This index is a snapshot as of 2026-10-25. It will go stale unless updated whenever a project's status changes materially — treat it as a map to re-check, not a live feed.

## Companion copy

A live, editable version of this same index also exists as a Claude Doc: https://claude.ai/artifact/HYiDrtKHDoxBGLsEiCP2q6 — update both when something changes.
