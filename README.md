<h1 align="center">
  <img src="https://avatars3.githubusercontent.com/u/4173285?s=200&v=4" alt="ZeroTierOne">
  <br />
  ZeroTierOne
</h1>

<p align="center"><b>This is the snap for ZeroTierOne</b>, <i>“Securely Connect Any Device, Anywhere”</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/fork-and-rename-me"><img src="https://build.snapcraft.io/badge/snapcrafters/fork-and-rename-me.svg" alt="Snap Status"></a>
</p>
-->

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->

<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

## Install

    sudo snap install zerotier
    sudo snap connect zerotier:network-control

NOTE: the snap connect command is necessary or you will be unable to use the /dev/tun needed for the connection.

### Join your network

    sudo zerotier.zerotier-cli join 8056c2e21c000001
    sudo zerotier.zerotier-cli status

Approve your new node in [ZeroTier Central](https://my.zerotier.com/)! Welcome online!


[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/zerotier)


([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Remaining tasks
<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) 
are working to land snap install documentation and
the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml)
upstream so [Project] can authoritatively publish future releases.

  - [x] Click the green "Use this template" button above to create a new repository based on this template
  - [x] Give the newly created repository a sensible name, like `godzilla-snap` if you're snapping the Godzilla software
  - [x] Update the description of the repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [ ] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [ ] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Make a post in the [Snapcraft Forum](https://forum.snapcraft.io) asking for a transfer of the snap name from you to snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [ ] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).


## The Snapcrafters

| [![capruro](http://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/capruro/) |
| :---: |
| [capruro](https://github.com/capruro/) |



## Upstream

| [![ZeroTierOne](https://avatars3.githubusercontent.com/u/4173285?s=200&v=4)](https://github.com/zerotier/ZeroTierOne) |
| :---: |
| [ZeroTierOne](https://github.com/zerotier/ZeroTierOne) |
