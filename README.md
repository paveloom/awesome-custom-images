# awesome-custom-images

This list is an attempt to organize and collect public configs of people's custom OStree native containers.
This will help others build their own and allow for us to learn from each other.

- [Fedora CoreOS Examples Repository](https://github.com/miabbott/coreos-layering-examples) - a collection of examples to start with and derive from, start here!

> **Warning**
> This is still a relatively new feature, take precautions when testing on an installation you care about. :smile:

## Configs

(In alphabetical order)

- [Alessandro Di Stefano (aleskandro)](https://github.com/aleskandro/my-ostree-config) - OSTree-native container configs for a custom Fedora Kinoite for personal use
- [Dallas Strouse (Oro)](https://github.com/orowith2os/uBlue-Budgie) - A WIP rpm-ostree image based on uBlue, for Budgie
- [Jorge Castro](https://github.com/ublue-os) - Community built OS images based on Fedora Silverblue
  - [base](https://github.com/ublue-os/base) - A base image you can start from
  - [ubuntu](https://github.com/ublue-os/ubuntu) - Fedora Silverblue for Ubuntu Expatriates
- [Kyle Gospo](https://github.com/KyleGospo)
  - [bazzite](https://github.com/KyleGospo/bazzite) - "Bazzite" may one day be an alternative OS for the Steam Deck based on Fedora Kinoite
  - [serverblue](https://github.com/KyleGospo/serverblue) - Fedora CoreOS with cockpit, podman-docker, automatic updates via rpm-ostreed, and services for duperemove/distrobox-upgrade/flatpak updates.
- [Martin Pitt](https://github.com/martinpitt)'s [SwayWM](https://swaywm.org/) desktop OSTree
     - [minimal ostree build from scratch](https://github.com/martinpitt/ostree-pitti-workstation) (production)
     - [experimental CoreOS fork](https://github.com/martinpitt/pitti-workstation-oci) (much simpler, still some bugs)
- [Pavel Sobolev (paveloom)](https://github.com/paveloom-d/paveloom-os) - An OSTree native container for personal use
- [Yosuke Matsumura (GuiltyDoggy)](https://github.com/GuiltyDoggy/ostree-container) - Proof of concept for custom image for rpm-ostree container-native deployment

## Documentation and Specifications

- Spec: [OStree Native Containers](https://fedoraproject.org/wiki/Changes/OstreeNativeContainer): Important!
- Spec: [Ostree Native Container (Phase 2, stable)](https://fedoraproject.org/wiki/Changes/OstreeNativeContainerStable): Important!

## Discussions

- [Feature for custom rpm-ostree container-native builds?](https://discussion.fedoraproject.org/t/feature-for-custom-rpm-ostree-container-native-builds/44480)

## Video Content

- [Silverblue's move to bootable OCI images](https://www.youtube.com/watch?v=X8h304Jp9N8)
- [Image-based customization with Fedora Silverblue](https://www.youtube.com/watch?v=9xO4w-w8mzg)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

If you don't know how to use git then file an issue and leave a link, I'll integrate it into the list!
