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
# Prerequisites
#+ needs devbox to be installed

# Checkout repo, change into kubernets directory and run:
devbox shell # Enter the shell
```