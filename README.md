# XBMCnfoTVImporter - Docker mod for plex

This mod adds [XBMCnfoTVImporter](https://github.com/gboudreau/XBMCnfoTVImporter.bundle) to Plex, to be downloaded/updated during container start.

In plex docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:plex-xbmcnfotvimporter`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:plex-xbmcnfotvimporter|linuxserver/mods:plex-mod2`