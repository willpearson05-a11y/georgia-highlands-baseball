# Georgia Highlands Baseball Analytics — 2026-27

TrackMan analytics hub for the Georgia Highlands Chargers (copied from the Murray State site, starting with an empty database).

## Setup
1. Create a new Supabase project with the same three tables as the Murray State project: `pitches`, `games`, `umpire_games` (Supabase → Table Editor, or copy the schema from the MSU project's SQL editor).
2. Edit `config.js`: paste the new project URL + anon key, and confirm the GHC TrackMan team code (`TEAM_CODE` / `TEAM_MATCH`).
3. Upload game CSVs through **TrackMan Data Files** (`ghc_csv_uploader.html`).
4. Replace `GHC-logo.png` with the official logo if you want it on reports.
