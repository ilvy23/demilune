# Dusk Player

**A local music player for Android that cares about how your music sounds.**
Your files, your folders, no account, no ads, no tracking. Bit-perfect USB output, word-by-word lyrics,
a listening timeline you can actually explore, and a lot of small details that make a big library feel good.

<p align="center">
  <img src="img/now-playing.jpg" width="230" alt="Now Playing: bit-perfect USB output with word-by-word lyrics">
  <img src="img/timeline.jpg" width="230" alt="Listening timeline">
  <img src="img/library.jpg" width="230" alt="Library">
</p>

> **Download:** [latest APK](https://github.com/ilvy23/dusk-releases/releases/latest) · Android 10 or newer · free
> After the first install the app updates itself.

---

## Screenshots

<p align="center">
  <img src="img/monthly-recap.jpg" width="230" alt="Monthly recap">
  <img src="img/smart-mixes.jpg" width="230" alt="Smart mixes">
  <img src="img/album.jpg" width="230" alt="Album page">
</p>
<p align="center">
  <img src="img/browse.jpg" width="230" alt="Browse: playlists, recently added, genres">
  <img src="img/stats.jpg" width="230" alt="Listening stats">
  <img src="img/settings.jpg" width="230" alt="Settings">
</p>

*Album covers shown are from the author's own library.*

---

## Highlights

**Sound**
- **Bit-perfect USB audio** with its own driver for UAC2 DACs and USB-C IEM cables: the file goes to the DAC untouched,
  with the DAC's own hardware volume. Automatic fallback to normal Android audio when a device cannot do it
  (for example simple USB-C dongles), so you always hear something.
- Hardware volume keys, headset buttons and Bluetooth controls work together with the bit-perfect path.
- Gapless playback, FLAC/ALAC/WAV/MP3/AAC/Opus/Vorbis, Hi-Res badges, safe-volume tools, sleep timer.
- Bluetooth, USB and wired headphones with automatic pause on unplug.

**Your library**
- Pick your music folder(s); Dusk reads only what is inside them. Rescans remove what is gone.
- Fast incremental scanning, collab artists folded into the main artist, spelling variants merged.
- Playlists, favorites, smart mixes, custom artist pictures with a crop tool (kept private, never in your gallery).
- Optional cover-file hiding (`cover.jpg` → `.cover.jpg`) so gallery apps stay clean.

**Lyrics**
- Synced lyrics, **word by word**, with accent colours taken from the cover.
- Optional English subtitles under every line for songs in other languages.
- Reads lyrics you already have (embedded tags, `.lrc` files, imported files). When you ask for a song's lyrics, Dusk looks them up on [LRCLIB](https://lrclib.net).

**Discover your own taste**
- **Timeline:** a winding path of your listening days, each with the album you played most. Tap a day and it opens into a
  tree of every song you heard that day. Pinch to zoom, as big as it gets.
- **Monthly recap**, listening stats, streaks, **Reels** (a vertical feed of 20–30 second moments from your own songs).
- Small games that play with your music (optional).

**Made to be light**
- Animations adapt to your phone: auto / full / reduced / performance mode. Runs on modest hardware.

---

## Requirements

| | Minimum | Recommended |
|---|---|---|
| Android | 10 (API 29) | 12 or newer |
| RAM | 3 GB | 6 GB or more (more cover caching and warm-up) |
| CPU | 64-bit or 32-bit ARM | any recent ARM64 phone |
| Storage | ~100 MB for the app | plus your music |
| Audio | any headphones, Bluetooth or USB | a USB DAC / USB-C IEM cable for bit-perfect |

**About USB devices**
- Bit-perfect is for **UAC2 USB DACs** (most dongle DACs and DSP cables). Developed and tested with the Moondrop DUSK
  USB-C cable on a Xiaomi 15T Pro.
- Simple adapters such as UAC1 dongles play through Android's normal audio path automatically.
- If a device misbehaves, Settings › Audio › USB audio mode lets you switch to "Android system output".
- Not every device combination has been tested. Reports are welcome, see below.

## Install

1. Open the link above on your phone and download the `.apk`.
2. Allow your browser to install apps when Android asks.
3. Open Dusk, choose your music folder, done.

Updates arrive by themselves (Settings › About › Check now). The app only contacts this page to see whether a new version exists.

## Privacy

- No account, no analytics, no ads. Your listening data never leaves your phone.
- The only network access: the update check against this repository (GitHub), and a lyrics lookup on LRCLIB **only when you ask for it**.
- You can turn the update check off.

## Known limits

- Closed source for now; the APK is signed so updates are verified.
- Some Android skins stop background apps aggressively; allow Dusk to ignore battery optimisation.
- Android 11 and older cannot discover Bluetooth devices for phone-to-phone transfer.

## Feedback and bug reports

Open an issue on this page and include: phone model, Android version, USB/Bluetooth device, and what you saw.
Please do not attach your music files.

---

*Dusk Player is an independent project and is not affiliated with Moondrop or any DAC or headphone maker.*
