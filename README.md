<h1 align="center">
  <img src="https://raw.githubusercontent.com/logseq/logseq/master/android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png" alt="Logseq">
  <br />
  Logseq
</h1>

<p align="center"><b>This is the snap for Logseq</b>, <i>“A privacy-first, open-source knowledge base that works on top of local plain-text Markdown and Org-mode files.”</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<a href="https://snapcraft.io/logseq">
  <img alt="logseq" src="https://snapcraft.io/logseq/badge.svg" />
</a>
<a href="https://snapcraft.io/logseq">
  <img alt="logseq" src="https://snapcraft.io/logseq/trending.svg?name=0" />
</a>

![logseq](screenshot.png?raw=true "logseq")

## Install

```bash
sudo snap install logseq
```

### Using GIT sync

In case you're using GIT sync with SSH authentication you may want to connect the `ssh-keys` interface with:

```bash
sudo snap connect logseq:ssh-keys
```

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/logseq)

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Logseq OG

[Logseq OG](https://github.com/logseq/og) is the original, file-based version of Logseq
that works on top of local plain-text Markdown and Org-mode files. It's preserved for users
who prefer it over the newer database-based release. It's published to the `og` track of this
same snap, so you can run it without affecting your default Logseq install. To install it:

```bash
sudo snap install logseq --channel=og
```

If you already have Logseq installed, switch to it with:

```bash
sudo snap refresh logseq --channel=og
```

To go back to the default release, refresh to the `latest` track:

```bash
sudo snap refresh logseq --channel=latest
```
