# audio-plugin-catalog
# Audio Plugin Catalog

This public repository contains the normalized catalog consumed by Audio Plugin Manager.

The catalog currently contains verified entries for Xfer Records, FabFilter, Soundtoys, and Sonic Charge. Entries are added only when the version and official update page can be verified. The catalog must not use unofficial mirrors or invented checksums.

The app endpoint is:

https://raw.githubusercontent.com/snsnsaim/audio-plugin-catalog/main/catalog.json

An entry without a verified download URL and SHA-256 is intentionally limited to opening the official vendor page. It must never be treated as an automatically installable update.

The current official source pages are:

- Xfer Records: https://support.xferrecords.com/article/35-how-do-i-update-serum
- FabFilter: https://www.fabfilter.com/download and https://www.fabfilter.com/support/downloads
- Soundtoys: https://www.soundtoys.com/soundtoys-5-4-3-update/
- Sonic Charge: https://soniccharge.com/download

Some vendors require an account or their own installer manager. Those entries intentionally open the official vendor page instead of downloading an unverified installer.
