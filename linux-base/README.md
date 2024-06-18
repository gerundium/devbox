# linux-base

- ✏️ This section helps you get devbox installed locally (not in a pod).

- ✏️ Packages and setting are being configured in ***devbox.json***

## Directory structure
```
.
├── devbox.json                         # Preconfigured config file for my linux-base environment
├── install                             # Requirements directory
│   └── sh.launchDevboxSingleUserMode   # Script that installs devbox (and nix) and runs the devbox shell
└── README.md                           # This readme file
```

## TL;DR;

Fastest way to deploy a devbox setup

```bash
# Clone this repository
git clone https://github.com/gerundium/devbox.git

# Install and run the devbox environment linux-base
bash install/sh.launchDevboxSingleUserMode

# After the initial run you can run this command to enter the environment
devbox shell # Enter the shell
zsh          # Switch from bash to preconfigured zsh
```