# Privacy Policy — Lyrica and Lyrica Bridge

_Last updated: October 17, 2026_

Lyrica (the Mac app) and Lyrica Bridge (the Chrome extension) are free and don't collect
data about you. There are no accounts, analytics, ads or trackers.

## What the extension reads

On music.youtube.com only, Lyrica Bridge reads:

- the current track's title, artist, album, artwork link and duration,
- the playback position and whether it's playing,
- the next song in your queue (to fetch its lyrics early),
- loudness levels of the playing audio, as numbers, ~50 times a second (so lyrics can line
  up automatically). **Audio is never recorded or transmitted.**

## Where it goes

Only to the Lyrica app **on the same computer**, over a local connection (`127.0.0.1`).
It is not sent to the developer or any third party, not sold, and not used for advertising.

## What the app sends over the internet

To find lyrics, Lyrica sends the track's **title, artist, album and duration** to:

- [LRCLIB](https://lrclib.net) and
- QQ Music's public lyrics search,

and loads artwork from Google's image servers (the same images YouTube Music shows).
If you choose **Publish to LRCLIB** after syncing lyrics yourself, those lyrics and timings
are published publicly and anonymously on lrclib.net — only after you confirm.

The app also checks GitHub for new versions of Lyrica.

## Stored on your Mac

Settings, timing offsets, cached lyrics and lyrics you synced are stored locally in
`~/Library/Application Support/Lyrica`. Delete that folder to remove them.

## Contact

Questions: open an issue on this repository.
