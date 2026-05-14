# flatbuddy

Flatpak development swiss army knife: Build, develop, update and debug flatpak applications easier.

```bash
flatbuddy --help
```

```bash
flatbuddy build
flatbuddy build [manifest.json, manifest.yaml, manifest.yml]
flatbuddy exec [manifest.json, manifest.yaml, manifest.yml] -- /bin/sh
flatbuddy lint [manifest.json, manifest.yaml, manifest.yml]
flatbuddy track [manifest.json, manifest.yaml, manifest.yml]
flatbuddy inspect [appid]
flatbuddy help
flatbuddy version
```

<!-- PLEASE finish this documentation, i dont know how to write stuff -->

## Installation

Clone this git repository somewhere in your filesystem

```bash
mkdir -p "${HOME}/opt/tulilirockz"
git clone "https://github.com/tulilirockz/flatbuddy" "${HOME}/opt/tulilirockz/flatbuddy"
```

Then you can symlink the vmbuddy script into somewhere in your `$PATH` variable:

```bash
ln -s "${PWD}/fb" "${HOME}/.local/bin/fb"
ln -s "${PWD}/flatbuddy" "${HOME}/.local/bin/flatbuddy"
```

This allows you to get updates by `git pull`.

