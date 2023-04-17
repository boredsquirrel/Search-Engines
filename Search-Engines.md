**Here is a list of regular Clearnet Search Engines**

# Friendly Search Engines

## Random SearX
This Engine redirects every search to a different SearX server, decentralizing your usage.
It may be a honeypot itself, but it allows you to use most available Engines evenly and makes you untrackable for Google & Co.

`https://searx.neocities.org/#q=%s&category_general=on`

### Random SearX Images:

`https://searx.neocities.org/#q=%s&category_images=on`

### Random SearX Videos:

`https://searx.neocities.org/#q=%s&category_videos=on`

### Random SearX Files:

`https://searx.neocities.org/#q=%s&category_files=on`

### Random SearX Maps (usefulness questionable):

`https://searx.neocities.org/#q=%s&category_maps=on`

*this can go on... Choose tags that all SearX instances support. Some are very specific*

***NOTE: Every instance chooses their crawled engines differently, so you may get unpleasing results. You may prefer having one instance with saved settings, enabled and disabled search engines.***

## Configure your favourite SearX instance
Pick any SearX or SearXNG instance you want ([searx.space](https://searx.space/))

Set your settings and either save the Cookies for this site (allow cookies for the Site in the Firefox Privacy settings) or copy the custom URL

### Startpage 
this one is more complicated, as you can store the settings in the URL but this only works using the less secure "GET" method. ([Wikipedia](http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods))

the default URL:

`https://www.startpage.com/sp/search?query=%s`

Under Settings you can add a custom region, Language, disable ads or censored mode:

1. Open settings
2. Change what you want
3. Choose "GET" instead of "POST"
4. Copy the URL on the right panel
5. Add `&query=%s` to the beginning of the URL

example:

`https://www.startpage.com/sp/search?query=%s&abp=-1&t=dark&lui=english&cat=web`

### Mullvad Leta
Only for Mullvad Customers, restricted to 50 searches a day. They have "search in Cache" mode, which is on by default, but this cache is deleted after 30 days so its not very useful for most results. Google API queries cost money so searching in cache is a good possibility, but you need to disable the tick every time, which is annoying.

No cache:

`https://leta.mullvad.net/?q=%s&oc=0`

Normal:

`https://leta.mullvad.net/?q=%s&oc=1`

### OpenStreetMaps

`https://www.openstreetmap.org/search?query=%s`

### Qwant Lite Images

`https://lite.qwant.com/?q=%s&t=images`

### Mojeek

`https://www.mojeek.com/search?q=%s`

### Wikipedia DE

`https://de.wikipedia.org/wiki/Spezial:Suche?fulltext=Artikel+suchen&fulltext=Search&search=%s`



# Privacy frontends
![Icon](https://addons.mozilla.org/user-media/addon_icons/2738/2738435-64.png?modified=042b804c)

Prefer using Libredirect instead of those, as you will pick random instances and decentralize your usage.

- [Firefox](https://addons.mozilla.org/en-US/firefox/addon/libredirect/)
- [Chromium](https://github.com/libredirect/libredirect/releases/latest)

Here are some to-be-redirected Search Engines:

(There are many more privacy frontends)

### Youtube

`https://youtube.com/search?q=%s`

### Twitter Users

`https://twitter.com/search?f=users&q=%s`

### Reddit

`https://www.reddit.com/search/?q=%s`

# Popular Platforms

### Rotten Tomatos

`https://www.rottentomatoes.com/search?search=%s`

# Tech 

### Alternative To

`https://alternativeto.net/browse/search/?q=%s`

### F-Droid

`https://search.f-droid.org/?q=%s`

### Flathub

`https://flathub.org/apps/search/%s`

[Other Flatpak sources](https://github.com/trytomakeyouprivate/Flatpak-remotes)

Search for Flathub Flatpak Code, Issues, Discussions:

`https://github.com/search?q=org%3Aflathub+%s`

### Appimages

[Github Page](https://appimage.github.io/apps/)


`https://www.linux-apps.com/find?search=%s`

### Crates.io precompiles Rust packages

`https://crates.io/search?q=%s`

### Arch Wiki

`https://wiki.archlinux.org/index.php?search=%s`

### NixOS Packages

`https://search.nixos.org/packages?type=packages&query=%s`

### Keys OpenPGP

`https://keys.openpgp.org/search?q=%s`

### KDE Gitlab

`https://invent.kde.org/search?search=%s&nav_source=navbar`

### Libreoffice Help

`https://help.libreoffice.org/7.2/de/search?P=%s`

### Fedora COPR repos

`https://copr.fedorainfracloud.org/coprs/fulltext/?fulltext=%s`

### Fedora Packages

`https://packages.fedoraproject.org/search?query=%s`

### Github

`https://github.com/search?q=%s`

### AUR

`https://aur.archlinux.org/packages?O=0&K=%s`

### ProtonDB
Playable Games using Valves Wine Version

`https://www.protondb.com/search?q=%s`

# Useful Tools

### Icons8

`https://icons8.com/icons/set/%s`

# Research

Any SciHub-Addon is recommended ;D

### Connected Papers

`https://www.connectedpapers.com/search?q=%s`

### Elsevier

`https://www.elsevier.com/de-de/search-results?query=%s`

### Pangaea

The Search engine works without Cloudflare JS, while the Start page doesnt want to work!

`https://pangaea.de/?q=%s`

### Semantic Scholar

`https://www.semanticscholar.org/search?q=%s&sort=relevance`

### Library Genesis

`https://libgen.lc/index.php?req=%s`

### Z-Lib (requires Account)

`https://b-ok.cc/s/%s?`
