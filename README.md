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

<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

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

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/snapcrafters-reboot/24625)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml) upstream so Logseq can authoritatively publish future releases.

  - [x] Click the green "Use this template" button above to create a new repository based on this template
  - [x] Give the newly created repository a sensible name, like `godzilla` if you're snapping the Godzilla software (*Note: Do not use `snap` in this name.*)
  - [x] Update the description of the repository to `Unofficial snap for [Project]`
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link]()
  - [ ] Add the Snapcraft store account (snap-advocacy@canonical.com) as a collaborator to your snap in the [Dashboard](https://dashboard.snapcraft.io) and ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to accept this request
  - [ ] Fix all important issues found during testing
  - [ ] Make a post in the Snapcraft Forum ["store-requests" category](https://forum.snapcraft.io/c/store-requests/19) asking for a transfer of the snap name from you to Snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link]()
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Ask upstream if they are interested in maintaining the Snap. If they are:
    - [ ] Fork the upstream project, add the snap build files and required assets/launchers to that repo and submit a pull request or patch - [link]()
    - [ ] Add upstream contact information to the `README.md`
    - If upstream accept the PR:
      - [ ] Request upstream create a Snap store account
      - [ ] Add upstream account as a collaborator on the snap
      - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

<!--
## The Snapcrafters

| [![Your Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431/?s=128)](https://github.com/yourname/) |
| :---: |
| [Your Name](https://github.com/yourname/) |
--> 

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->
