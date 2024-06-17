# devpod

## Directory structure
```
.
├── docker-compose.yaml   # Docker compose file
├── Dockerfile            # Container source for docker image
├── makefile              # Automation tool
├── motd                  # Image content
├── README.md
├── sh.launchDevbox       # Bootstrap devbox shell
└── zshrc                 # Image content
```

## TL;DR;

Fastest way to deploy a devbox setup

```bash
# Clone this repository
git clone https://github.com/gerundium/devbox.git

# Run a devbox pod directly
docker run -it --rm --net host <YOUR-IMAGE>
# or run my prebuild image (eiboo9uu/devpod) via docker compose
docker compose run devpod
```