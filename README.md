# Aurabeat

Ambient light, synced lyrics and a music wallpaper for whatever you're playing on Windows 10 and 11: Spotify, Apple
Music, Amazon Music, YouTube Music or SoundCloud in your browser, or anything else that shows up in Windows' media
controls.

- **Edge light**: a glow around your screens in the album's colours, pulsing with the beat.
- **Synced lyrics** that fill in word by word as they're sung, floating at the bottom of your screen.
- **Music wallpaper**: the song's music video (or its album cover) behind your desktop icons, in time with the
  music. Or a turntable spinning the record, which you can scratch through and turn the volume up on.
- **Every display your way**: each screen shows the video, the album cover, the turntable, nothing, or **side by
  side**: two halves, each the video, the turntable, the album cover or big word-by-word lyrics. Behind it all: a
  blurred cover, black, white, or your own (even live) wallpaper.
- **Music selector**: browse your Spotify albums and playlists as floating 3D covers.
- **Customise** the lyrics, the light's colours and Aurabeat's own look.

## Install

1. Open the [latest release](https://github.com/arcular/aurabeat/releases/latest) and download **Aurabeat-Setup.exe**.
2. Run it. Aurabeat installs for your Windows account (no admin needed) and starts. It lives by the clock, in the
   tray (it may be under the `^` arrow).

   Windows may say *"Windows protected your PC"*, because Aurabeat isn't signed with a paid certificate. Click
   **More info**, then **Run anyway**.

Aurabeat updates itself: when a new version is out, it downloads it in the background, and the music selector offers
to restart into it.

**Uninstall**: Settings → Apps → Aurabeat → Uninstall. This also removes its settings and saved sign-ins.

## Spotify

Open the music selector (right-click the tray icon → **Browse music…**) and click **Connect Spotify**. You sign in with
your own Spotify account on Spotify's own page; Aurabeat never sees your password.

Spotify only lets invited accounts use an app like Aurabeat. If it says yours isn't on the list, send the person who
shared Aurabeat with you the email address of your Spotify account so they can add it, then connect again. Or click
**Use my own Spotify app** and follow the steps (a few minutes, once).

Playing songs from the selector needs Spotify Premium (Spotify's rule). Everything else works with any account, and
with other music apps too.

## Music videos

Right-click the tray icon → **Set up music videos…** and follow the four steps to get a free YouTube key from Google
(about 3 minutes, once). Without one, you get the album cover instead.

## Privacy

- Aurabeat listens to your PC's sound output to find the beat. It never uses the microphone, and nothing is recorded.
- To find lyrics it sends the song's name, artist and length to lrclib.net; to find videos, the song's name and artist
  to YouTube.
- Your settings and sign-ins stay on your PC, in `%LOCALAPPDATA%\Aurabeat`. Sign-ins are encrypted for your Windows
  account.
