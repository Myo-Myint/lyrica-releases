# Lyrica

Beautiful, time-synced lyrics for YouTube Music on your Mac: word-by-word highlighting,
full screen on a big display, a floating mini bar, romanization and translation, and lyrics
that line themselves up with the song.

Free. For macOS on Apple Silicon (M1 and later) and Intel Macs.

**Website and demo:** https://myo-myint.github.io/lyrica-releases/

## Install

1. **Download** from the [latest release](../../releases/latest):
   - `Lyrica-<version>-arm64.dmg` for Apple Silicon Macs (M1, M2, M3, M4 and later)
   - `Lyrica-<version>-x64.dmg` for Intel Macs

   Not sure which Mac you have? Apple menu → About This Mac: "Chip: Apple M…" means arm64,
   "Processor: … Intel" means x64.
2. Open the DMG and drag **Lyrica** into **Applications**.
3. **First launch only:** this early version isn't notarized by Apple yet, so macOS asks you
   to confirm it once:
   1. Open Lyrica from Applications. macOS says it can't verify the app — click **Done**.
   2. Open **System Settings → Privacy & Security**, scroll down to the Lyrica message, and
      click **Open Anyway**, then confirm.

   After that, Lyrica opens normally.
4. **Add the browser extension** _Lyrica Bridge_. Its Chrome Web Store listing is in review
   (link coming soon); until then Lyrica's Setup Guide walks you through loading it. It works
   in **Chrome, Edge, Brave, Arc, Opera and Vivaldi**, which all install Chrome extensions.
5. Play a song on [music.youtube.com](https://music.youtube.com). Lyrics appear in Lyrica.

## Using it

| | |
|---|---|
| **Play / pause, ±10 s, previous / next** | Space · ← / → · ⇧← / ⇧→ |
| **Full screen on another display** | menu-bar icon → *Show on Display*, then **F** |
| **Cover view** (artwork as the hero) | **C**, or click the artwork |
| **Mini lyrics bar** over every window | **M** in Lyrica, or **⌥⌘L** from anywhere |
| **Romanization / translation** under each line | **T** (translation language: menu-bar icon → *Lyrics* → *Translate To*) |
| **Text size** | **+** / **−** (or menu-bar icon → *Lyrics*) |
| **Font** (system, rounded, serif) | menu-bar icon → *Lyrics* |
| **Share a line** as an image | right-click the line, or **S** for the current one |
| **Lyrics timing off?** | − / + in the top bar nudges this song; ⌥ − / + adjusts for your headphones (e.g. AirPods) |
| **No lyrics?** | *Sync it yourself*: paste the words and tap Space as each line starts |

## Updates

Lyrica checks this page and tells you when a new version is out (menu-bar icon → *Update
Available*). Download it and replace the app in Applications.

## Problems or ideas

[Open an issue](../../issues/new/choose). For bugs, click the menu-bar icon → **Copy
Diagnostics** and paste it in: it lists the app and extension versions and which lyrics
sources were tried, which makes most problems quick to find.

## Privacy

See [PRIVACY.md](PRIVACY.md). In short: nothing about your listening leaves your Mac except
title/artist lookups to lyrics services, and lyric text to Google Translate only while
romanization or translation is switched on.
