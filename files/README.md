# peertube-theme-pacerip

## About

This repo contains the theme of the PaceRIP PeerTube instance ([pace.rip](https://pace.rip/)), formatted in accordance with the [PeerTube docs](https://docs.joinpeertube.org/contribute-plugins?id=write-a-plugintheme).

## Important disclaimer

PaceRIP is a streaming-only no-VODs instance! Installing the theme unmodified will hide will prevent users from uploading videos. (Although "prevent" is a strong word, this theme simply hides the upload button.)

## Installation for PeerTube instances

1. [Search for](https://pace.rip/admin/plugins/search?pluginType=2) the `pacerip` theme and install.
2. If desired, change your instance's default theme under `Administration > Configuration > Basic configuration > Appearance`.

## Update your theme version manually

1. [Uninstall](https://pace.rip/admin/plugins/list-installed?pluginType=2) the theme, then repeat the above installation steps.

## A brief CSS note

`style.css` is messy! And minimization breaks it for some reason. So for now, you folks are gonna have to deal with some shabby CSS styling, boo-hoo.

## NPM specifics

Whenever this repo is updated, the npm maintainer must run `git fetch` and `npm publish` to update the associated npm package. As such, new versions must include an updated version number within `package.json`.

[You can find the theme's npm package here.](https://www.npmjs.com/package/peertube-theme-pacerip)

Also! The weird directory structure of this repo is to accommodate `peertube-theme-pacerip-light-dark-flip`.