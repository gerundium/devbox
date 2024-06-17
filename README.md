# devbox

## TL;DR;

```bash
git clone https://github.com/gerundium/devbox.git
cd dbcDevPod
make build-x86

docker run -it --rm --net host <YOUR-IMAGE>
# or run via docker compose (eiboo9uu/devpod)
docker compose run devpod
```