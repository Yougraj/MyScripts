## Awesome Tools for Your Arch System

Welcome to the ultimate collection of tools for your Arch system! 🎉 Whether you're a pro or a beginner, these tools are here to make your life easier and your system more fun. Ready? Let's dive in!

### Screenshot Tool: scrot
#### Installation:
```bash
yay -S scrot 
```

Scrot is like the magic wand for capturing your screen. It’s quick, simple, and doesn't come with any fancy frills—just pure screenshotting power. Perfect for when you need to capture that "oops, I did it again" moment.
### Brightness Tool: brillo

#### Installation:
```bash
yay -S brillo
```

Feeling like your screen is a bit too bright or too dim? Brillo's got you covered. Adjust your screen brightness like a pro and keep your eyes from burning out! Remember: It's not the sun; it's just your monitor.

### Spotify Tool: spt
#### Prerequisites:
##### 1. Install rofi:
```bash
sudo pacman -S rofi
```
##### 2. Set up environment variables:
Add these to your environment 
```bash
variables:CLIENT_ID = os.environ.get("SPOTIPY_CLIENT_ID")
CLIENT_SECRET = os.environ.get("SPOTIPY_CLIENT_SECRET")
```
##### 3. Install Python dependencies:
```bash
pip install importlib tqdm spotipy urllib3 argparse
```
$Note$: This tool needs rofi to work its magic. If you don’t have it, you might miss out on some cool features.File 

$Location$: .local/bin

Spotify Tool is here to make sure your music is always on point. It’s like having your personal DJ, minus the awkward small talk. Just remember, it can’t actually DJ your next party, but it’ll make sure you’ve got the perfect playlist.
