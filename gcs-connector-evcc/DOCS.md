# GCS evcc Connector

Syncs completed evcc charging sessions to the [Green Charging Society (GCS)](https://github.com/larknafets/gcs-platform) platform — a peer-to-peer network for sharing charging power for free between wallbox owners.

This add-on wraps [gcs-connector-evcc](https://github.com/larknafets/gcs-connector-evcc). All configuration happens through this add-on's **Options** tab — no `.env` file, no setup wizard needed.

The connector's `state.json` (its sync watermark) is stored in this add-on's own config folder, reachable on the host under `app_configs/gcs-connector-evcc` (e.g. via the Samba or SSH & Web Terminal add-ons) — not in the add-on's private, hidden data folder.

For full details on how the connector works and its configuration options, see the [gcs-connector-evcc README](https://github.com/larknafets/gcs-connector-evcc#readme).
