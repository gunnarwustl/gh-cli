# gh-cli

## Usage

```bash
# show usage
$ docker run -it --rm ghcr.io/gunnarwustl/gh-cli:ubuntu20
```

```bash
# list available PRs
$ docker run -it --rm -v $HOME:$HOME -w $HOME -u $UID:$GID ghcr.io/gunnarwustl/gh-cli:ubuntu20 pr list
```
