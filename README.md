# Lotus AI Windows Agent releases

Installer packages for the Lotus AI Windows Agent, published as GitHub Releases, plus a mirror
copy of the agent's self-update feed.

- **Download the agent:** https://downloads.lotusai.co/agent/windows/
- **Update feed:** `https://downloads.lotusai.co/agent/windows/updates.txt` (primary).
  `updates.txt` in this repo is the same feed, read by installed agents if the primary host is
  unreachable.
- Releases tagged `-staging` are pre-release builds for upgrade testing, not for use.

Everything here is written by the release script (`Advanced Installer\Publish-Release.ps1` in
the agent's source repo). Don't edit it by hand: the feed's sizes and hashes must match the
signed packages exactly.
