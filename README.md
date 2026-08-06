# audio-plugin-catalog
# Audio Plugin Catalog

This public repository contains the normalized catalog consumed by Audio Plugin Manager.

The current seed contains only Xfer Records Serum entries whose installed bundle identifiers were observed on the development Mac. Entries are added only when the version and official update page can be verified. The catalog must not use unofficial mirrors or invented checksums.

The app endpoint is:

https://raw.githubusercontent.com/snsnsaim/audio-plugin-catalog/main/catalog.json

An entry without a verified download URL and SHA-256 is intentionally limited to opening the official vendor page. It must never be treated as an automatically installable update.
