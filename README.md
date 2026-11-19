# ClipForge

ClipForge turns long streams and videos into vertical clips for TikTok, Reels and Shorts. It finds the best
moments, cuts them, and adds word-by-word captions and a hook title. It also clips live streams as they happen.
Everything runs on your own PC: your videos never leave it.

Made by **Ganesh Deshmukh**.

## Download

**[ClipForge-Setup-1.0.0.exe](../../releases/download/v1.0.0/ClipForge-Setup-1.0.0.exe)** (836 MB, Windows 10 / 11, 64-bit),
or open the [release page](../../releases/tag/v1.0.0).

## What you need

- Windows 10 or 11, 64-bit
- An NVIDIA graphics card (RTX, 8 GB of video memory recommended) with a recent driver
- [Ollama](https://ollama.com) with a judge model: the system check on the first start says which
- About 5 GB of free disk space for the speech model (downloaded on the first start) and your clips

## Install

1. Run `ClipForge-Setup-1.0.0.exe`. It installs for your Windows account only (no administrator rights).
   The installer is not code-signed: if Windows SmartScreen stops it, click **More info**, then **Run anyway**.
2. Open ClipForge from the Start menu or the desktop. On the first start, click **Run the system check**: it
   downloads the speech model and measures your PC.
3. Paste a YouTube, Twitch or Kick link (or drop a video file) and click **Make clips**.

## Trial and license

Without a license key ClipForge is a trial: it makes **3 clips** in all. The clips it made stay yours: play,
edit and export them.

For the full version: open **Settings** (the gear, top right), then **About**, click **Copy** next to
"This PC's code" and send that code to Ganesh Deshmukh. Paste the license key you get back under
**License key** and click **Activate**. A key works on the PC it was made for.

## Open-source software inside

ClipForge includes open-source software, each part under its own licence (the licences are installed with the
app: **Settings, About, Show licences**):

- **FFmpeg** 9.0.2, the "full" build by [gyan.dev](https://www.gyan.dev/ffmpeg/builds/), licensed under the
  GNU GPL version 3. Its source code: [ffmpeg-9.0.2.tar.xz](https://ffmpeg.org/releases/ffmpeg-9.0.2.tar.xz)
  from ffmpeg.org. For three years from this release, the complete source of the FFmpeg build in this installer
  is available on request: open an issue in this repository.
- yt-dlp (the Unlicense), faster-whisper and CTranslate2 (MIT), Electron (MIT) and Chromium (BSD-style), the
  Noto Sans, Poppins, Anton and DM Serif Display fonts (SIL Open Font License), NVIDIA cuBLAS (redistributed
  under the NVIDIA CUDA Toolkit licence).

Use ClipForge only on videos you have the right to clip (your own, or footage a creator or campaign allows).
