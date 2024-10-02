# Devbox - Starship

## Prerequisites
- Install any NerfFont and configure it on your terminal emulation to satifiy the font requirements.
- Currently I prefer 'Lilex'

```bash
# Create a user-based font directory
mkdir -p ~/.local/share/fonts/

# Download the font
cd /tmp/
curl -OL https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Monaspace.zip

# Install font
## Favorite: MonaspiceNe Nerd Font Mono
unzip Monaspace.zip -d ~/.local/share/fonts/Monaspace

# Rebuild fontcache
fc-cache -f -v
```

## Usage

```bash
devbox shell -c PATH/TO/YOUR/devbox/starship/devbox.json
```
