# Raspberry Pi Repo Manifest

## How to

### Install repo

To use this manifest repo, the 'repo' tool must be installed first.

```bash
mkdir ~/bin
curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
chmod a+x ~/bin/repo
PATH=${PATH}:~/bin
```

### Sync Repo

```bash
mkdir yocto-raspberrypi
cd yocto-raspberrypi
repo init -u https://github.com/tmoore3/raspberrypi-manifest.git
repo sync
```
