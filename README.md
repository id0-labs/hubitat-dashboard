# hubitat-dashboard

Hubitat Dashboard UI tweaks - a collection of modern "skins" for Hubitat Dashboard.  

- *smartly* - loosely based on the modern SmartThings app, with some direction from ActionTiles Slate skin.

### Getting Started

As there isn't an actual 'skin' system for Hubitat Dashboard, the easiest way to use these skins is to create a new dashboard then following the copy and paste instructions.  If you would like to keep your existing tiles, you'll need to backup your "tiles:[]" data from your existing JSON, and replace the empty "tiles:[]" line in our JSON.

### Installing

- Copy and paste the contents of .json into Options > Advanced > Layout then 'Save JSON'.
- Copy and paste the contents of .css into Options > Advanced > CSS then 'Save CSS'.

### Fonts and Background Images

To truly have everything under one roof, you'll need to host the /assets folder locally and update your css and json to reflect the local url of those files.   Font references are at the start of the CSS file, and background image is at the end of the JSON.

## Changelog

- *smartly*
> 1/15/2020 - Initial commit

## Authors

* **Eli Altman** - *Initial work* - smartly
