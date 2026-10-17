# rajvirb.github.io

Redirect only. **Team Picker** has moved from `https://rajvirb.github.io/football_team_picker/` to
**https://playrs.app/** (hosted on Cloudflare).

- `football_team_picker/index.html`: sends old links to the new address, keeping the `#/screen` part of the link. When opened from an old Home Screen icon, it shows re-install steps instead.
- `football_team_picker/sw.js`: replaces the old app's service worker on phones, clearing its offline cache.
- `404.html` and `index.html`: send any other old link to the new address.

This repository contains no application code.
