# Luminity-Alerts
Luminity is an app that tells you when dangerus weather is on the way. It checks the National Weather Service every 30 seconds, then a window pops up and a voice reads the alert out loud. You pick what alerts and states you want, and block the ones you dont. Each alert level has its own sound, and the windows can close on there own.
Install and run

Requires Python 3.8+ with Tkinter. The app only uses the standard library, so pygame is optional (better mp3/ogg playback for custom sounds).

### Windows (PowerShell)
```
winget install -e --id Python.Python.3.12
```
Close PowerShell and open it again, then:
```
py -m pip install pygame


### Linux (Ubuntu / Debian)
```
sudo apt update && sudo apt install -y python3 python3-tk python3-pygame espeak-ng pulseaudio-utils ffmpeg


### macOS (needs Homebrew)
```
brew install python python-tk && python3 -m pip install --break-system-packages pygame

Voice and sounds use your OS's built-in tools on Windows and Mac. Linux needs `espeak-ng` for the voice, which the command above installs.
