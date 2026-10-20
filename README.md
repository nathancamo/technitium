# technitium

Blocklist for Technitium DNS (minipc + ThinkCentre), focused on ads and trackers that show up in the Grindr iOS app.

- `blocklist.txt` — the list Technitium subscribes to. Updated nightly at 12am Melbourne time by a Claude scheduled task.
- `allowlist-safety.txt` — domains that must never be blocked.

## Subscribe a Technitium server

Settings → Blocking → Block List URLs, add:

    https://raw.githubusercontent.com/nathancamo/technitium/main/blocklist.txt

Set the update interval to a few hours and save. Do this on both servers so they stay identical.
Every change is a git commit, so anything blocked by mistake is easy to find and revert.
