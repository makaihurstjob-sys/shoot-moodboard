# Shoot Mood Board

Sticky-note mood board and plan for the Alton Mason x 2010s A$AP Instagram shoot (Huntsville).

Live: https://makaihurstjob-sys.github.io/shoot-moodboard/

- **Board**: tap 🔥 / 👎 on a note to vote, 💬 or the photo to comment. Red × rips it off (only on your device).
- **Plan**: shared lists for date, crew, locations, shot list, fits, gear, budget (with total) and to-dos.
- **+ Add**: upload pics from your phone or paste a Pinterest link. Everyone sees them.

Shared data lives in the Supabase project "Shoot Moodboard" (tables `pins`, `reactions`, `comments`, `plan_items`; bucket `pins`; edge function `resolve-pin`). Photos committed to `photos/` also show on the board.
