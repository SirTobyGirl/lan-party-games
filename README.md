# LAN Party game files

This repo's releases hold the LAN Party games:

- `server`: game, hub and announcer packages plus `manifest.json`. Every LAN Party hub checks this and updates itself between games.
- `games`: the handheld game files, named `<game>.<file>.<sha256 prefix>`.

Both are uploaded by `hub/tools/publish.py` in the LAN Party project.
