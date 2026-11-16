# map
This is the main map of restaurants: The Nines' dinners, scored by members (map.thenines.club).

- Restaurant data comes from a published Google Sheet (`SHEET_URL` in `index.html`).
- Every restaurant row carries `club_id = 1` (The Nines), the same club ids as the members site
  (site.thenines.club). A `club_id` column in the sheet, if one is added, takes precedence.
- **Planned, not built:** the map stays public for now. Later, members signed in to their club may see
  extra detail about their own club's dinners; the `club_id` on each row is what that will use.
