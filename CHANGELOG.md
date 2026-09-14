# Changelog

Vibe Corgi for Mac, newest first. Each build is the DMG on [vibecorgi.net](https://vibecorgi.net) and the Homebrew cask `tuziani/tap/vibe-corgi`.

## 0.1.1 (16) — 2026-09-12

- Daily version check: once a day the app fetches `version.json` from this site and, if a newer build exists, shows a row in the menu that opens the download page. Nothing is downloaded or installed for you, the request carries no identifier, and the check can be switched off in the menu.
- The bark: the corgi now sounds once per thing that needs you — a session waiting on your answer, or a quota running out — and stays quiet while it is still there. One owner's log had 92 barks in a day; the same day now gives a handful.
- Quota flicker: Claude Code meters usage per model tier, and two tiers reporting in turn made the corgi flip between hungry and happy every few seconds. Readings are now kept per tier and merged, so the badge holds steady.
- Settings that stay put: the app used to write all of its settings back every two seconds while the dog walked, so a stale copy could silently restore values you had just changed — discreet mode included. Only the keys that actually changed are written now.

## 0.1.0 (13) — 2026-09-09

- First release on vibecorgi.net: the corgi along the bottom edge of your Mac, seven moods, Claude Code and Codex, a click that jumps to the right terminal, approving from the dog, four styles, dog sounds and 28 languages.
