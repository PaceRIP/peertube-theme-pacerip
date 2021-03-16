# peertube-theme-pacerip

## About

This repo contains the theme of the PaceRIP PeerTube instance ([pace.rip](https://pace.rip/)), formatted in accordance with the [PeerTube docs](https://docs.joinpeertube.org/contribute-plugins?id=write-a-plugintheme).

## Installation for PeerTube instances

1. [Search for](https://pace.rip/admin/plugins/search?pluginType=2) the `pacerip` theme and install.
2. If desired, change your instance's default theme under `Administration > Configuration > Basic configuration > Appearance`.

## Update your theme version manually

1. [Uninstall](https://pace.rip/admin/plugins/list-installed?pluginType=2) the theme, then repeat the above installation steps.

## CSS specifics

`style.css` is a minified version of `style.max.css`. PeerTube's formatting is affected by a file named `style.css`, and we skirt formatting rules for this purpose.

## NPM specifics

Whenever this repo is updated, the npm maintainer must run `git fetch` and `npm publish` to update the associated npm package. As such, new versions must include an updated version number within `package.json`.

[You can find the theme's npm package here.](https://www.npmjs.com/package/peertube-theme-pacerip)