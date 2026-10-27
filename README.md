# Torflix for Scoop

The official Scoop bucket for [Torflix](https://github.com/gary23w/torflix), a torrent video player and downloader for Windows.

```powershell
scoop bucket add torflix https://github.com/gary23w/scoop-torflix
scoop install torflix/torflix
```

The package installs the portable Windows build for x64 or arm64, verifies its SHA-256 checksum, creates a Start menu shortcut, and provides the `torflix` command. Playback history and settings use Torflix's normal local application-data folder.

For Dolby/DTS audio conversion, FFmpeg can be installed separately:

```powershell
scoop install ffmpeg
```

Only download or stream content you are authorized to access.

Source, release notes and support: [gary23w/torflix](https://github.com/gary23w/torflix).

Contact: info@garrettstimpson.ca

License: MIT OR Apache-2.0.
