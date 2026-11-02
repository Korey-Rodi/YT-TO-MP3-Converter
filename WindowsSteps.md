# Installs, Pre-Reqs, Use

## Install yt-dlp
```powershell
winget install --source winget --id yt-dlp.yt-dlp
```

## install FFmpeg
```powershell
winget install Gyan.FFmpeg
```
## Test installs

```powershell
yt-dlp --version
ffmpeg --version
```

## Navigate to Desktop on PC
```powershell
cd ./Desktop
```

## Paste the command with desired youtube link
```powershell
yt-dlp -x --audio-format mp3 "LINK_GOES_HERE"
```
