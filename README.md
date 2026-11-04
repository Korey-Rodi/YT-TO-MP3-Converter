# YT-TO-MP3-Converter tool via command line
### DO NOT RUN COMMANDS IN YOUR TERMINAL THAT YOU DO NOT UNDERSTAND; REVIEW EACH COMMAND BEFORE RUNNING TO ENSURE IT IS SAFE FOR YOUR DEVICE
## PRE-REQS (Installs and Verification) Mac Version
## Install homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### Uninstall homebrew if needed
Utitlize this command if the homebrew installation failed or you did not correctly set path variables
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/uninstall.sh)"
```
## Install yt-dlp and ffmpeg
```bash
brew install yt-dlp ffmpeg
```
## Install yt-dlp
```powershell
winget install --source winget --id yt-dlp.yt-dlp
```
<hr>

## PRE-REQS (Installs and Verification) Windows Version

## Install FFmpeg
```powershell
winget install Gyan.FFmpeg
```
## Test installs
```bash
yt-dlp --version
ffmpeg --version
```
<hr>

## STEP 1
For previous steps Refer to the steps file for the respective operating system
Follow each one to ensure that the installs were completed
(Note: this install requires you to have admin rights on the PC)

## STEP 2
Navigate to your desktop in the terminal using cd ./Desktop (This is where the downloaded files will go; if you wish to have them somewhere else make sure you are in the desired directory)
```bash
cd ./Desktop
```

## STEP 3
Run the command => yt-dlp -x --audio-format mp3 "LINK_GOES_HERE"
This will begin the download of the desired files and store them as an MP3; If you wish to save them as WAV change mp3 to Wav in the command
```bash
yt-dlp -x --audio-format mp3 "LINK_GOES_HERE"
```

## STEP 4
Take note of when the desired file is downloaded to your desktop the command will run through every song in a playlist regardless if that is desired
use Control + C to cancel the process and stop further downloads
