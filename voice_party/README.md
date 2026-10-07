# Voice Party public game content

- `levels.json`: 30 levels, 3 rounds each. Each round has an editable `audioUrl`.
- `audio/level_001.wav` to `audio/level_030.wav`: original synthesized placeholder sounds. You can replace a file in GitHub with your own WAV or change `audioUrl` to an HTTPS MP3, WAV or M4A.
- The Flutter game fetches JSON from GitHub at battle start and falls back to cached/bundled levels when offline.
- Keep `schemaVersion: 1`, level numbers and `rounds` structure intact.
- Raw GitHub CDN changes may take a few minutes to refresh.
