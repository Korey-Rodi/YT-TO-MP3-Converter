# Installs, Pre-Reqs, Use

## Install homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install yt-dlp and ffmpeg
```bash
brew install yt-dlp ffmpeg
```
## Test installs
```bash
yt-dlp --version
ffmpeg --version
```

## Navigate to Desktop on PC
```bash
cd ./Desktop
```

## Paste the command with desired youtube link
```bash
yt-dlp -x --audio-format mp3 "LINK_GOES_HERE"
```
