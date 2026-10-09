# Watch firmware releases

Binaries only: the source code lives in private repositories. Everything here
is written by the release workflows of the firmware projects.

| Product | Catalog (read by the devices) |
|---|---|
| SenseCAP Watcher W1-A | [`watcher.json`](watcher.json) |
| AMOLED Watch (Waveshare ESP32-S3-Touch-AMOLED-1.8) | [`amoled.json`](amoled.json) |
| ePaper clock (Waveshare ESP32-S3-ePaper-1.54 V2) | [`epaper.json`](epaper.json) |

Each catalog lists every release (newest first) and the newest of each channel:

- **stable**: versions `X.Y.Z`
- **dev**: test builds `X.Y.Z-dev.N` (marked "pre-release")

The `.bin` files are attached to the [releases](../../releases): tags
`watcher-vX.Y.Z`, `amoled-vX.Y.Z`, `epaper-vX.Y.Z`. Each release also has a zip for
flashing over USB (`esptool ... write-flash @flash_args`).
