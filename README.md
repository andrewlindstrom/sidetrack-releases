# Sidetrack

A music player that lives in your Mac's menu bar. You describe a station ("late-night city pop, but not the obvious hits") and a DJ, Claude, picks the songs, reads your thumbs and skips, and keeps the queue going. It plays through Spotify or Apple Music, in a Winamp-style Retro look or a clean Modern one.

## What you need

- A Mac on macOS 15 (Sequoia) or later.
- **One music service:**
  - **Spotify Premium**, plus a free Spotify developer app of your own (Sidetrack's Settings walks you through pasting its Client ID; the redirect URI is `http://127.0.0.1:43824/callback`), or
  - an **Apple Music** subscription on the Apple Account signed in to your Mac.
- **Claude Code**, installed and signed in with a Claude plan that includes it (Pro or Max): `curl -fsSL https://claude.ai/install.sh | bash`, then run `claude` once to sign in. The DJ runs on your own plan.

## Install

1. Download `Sidetrack-<version>.zip` from the [latest release](https://github.com/andrewlindstrom/sidetrack-releases/releases/latest).
2. Unzip it and drag **Sidetrack** into your **Applications** folder.
3. Open it. Its icon appears in the menu bar: click it for the player, right-click for Settings and Quit.

## Updates

Sidetrack checks for new versions about once a day and offers to install them; you can also right-click the menu bar icon and choose **Check for Updates…**.
