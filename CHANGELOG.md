### Added:
- Apps:
  - Games: Pinball0 (by @rdefeo)
  - NFC: Metroflip (by @luu176)
- UL: Sub-GHz: Jolly Motors support with add manually (by @pkooiman & @xMasterX)
- OFW: Desktop: Add winter animations (by @Astrrra)
- OFW: Furi: Pipe support (by @portasynthinca3)
- OFW: Furi: Thread stdin support (by @portasynthinca3)
- OFW: RPC: Command to send a signal once (by @Astrrra)
- OFW: API: Added `flipper_format_write_empty_line()` (by @janwiesemann)
- OFW: Add VCP break support (by @gsurkov)

### Updated:
- Apps:
  - BT/USB Remote: Add PTT support for Gather (by @SapphicCode)
  - Chess: Fix illegal move bug (by @956MB)
  - ESP Flasher: Add c3 and c6 to s3 option (by @jaylikesbunda), update Marauder bins to 1.1.0 (by @justcallmekoko)
  - FlipBIP: Refactor to make adding coins easier (by @xtruan)
  - FlipLibrary: Wikipedia, dog facts, random quotes, weather, asset price, predictions, trivia, advice, uuid and many more, bug fixes (by @jblanked), holidays, improvements to connectivity and progress (by @jamisonderek)
  - FlipSocial: Improved authentication, loading screens, memory fixes, bio and friend counts, search contacts (by @jblanked), RPC_KEYBOAARD support (by @jamisonderek)
  - FlipStore: Many bugfixes, support ESP32 firmware downloads, allow deleting apps, memory fixes, update Marauder (by @jblanked), more improvements (by @jamisonderek)
  - FlipTrader: Improved progress display, added connectivity check on startup (by @jamisonderek)
  - FlipWeather: Stability improvements (by @jblanked), improved progress display, added connectivity check on startup (by @jamisonderek)
  - FlipWiFi: Improve error handling, update scan loading and parsing, fix crash when saving networks manually (by @jblanked), add connectivity check on startup (by @jamisonderek)
  - Pokemon Trade Tool: Update to gblink v0.63 which includes saving/loading of pin configurations for the EXT link interface (by @kbembedded)
  - Snake 2.0: Progress saving, endless mode, game timer, fruit positioning bugfixes (by @Willzvul)
  - uPython: Enabled extra functions for the `random` module (by @ofabel)
  - WebCrawler: Improved progress display, added connectivity check on startup (by @jamisonderek)
  - WiFi Marauder: AirTag Spoof, flipper blespam, sniff airtag and flipper, list airtag (by @0xchocolate)
  - UL: NFC Magic: Added possibility to write 7b MFC to Gen1 tags (by @mishamyte)
  - UL: Unitemp: Fixed handling of hPa units (by @shininghero)
  - UL: Fixed apps for firmware USB CDC callback changes (by @xMasterX)
- NFC:
  - OFW: Replace mf_classic_dict.nfc with Proxmark3 version (by @onovy)
  - OFW: More station IDs for Clipper plugin (by @ted-logan)
- OFW: Infrared: Add IR command for NAD DR2 D7050 D3020 (by @nikos9742)

### Fixed:
- Desktop: Fixed Wardriving animation design (by @Davim09)
- OFW: Fix lost BadBLE keystrokes (by @Astrrra)
- OFW: GPIO: Fix USB UART Bridge Crash by increasing system stack size (by @Astrrra)
- OFW: Loader: Fix BusFault in handling of OOM (by @Willy-JL)
- NFC:
  - OFW: Plantain parser Last payment amount fix (by @mxcdoam)
  - OFW: Fix skylander ID reading (by @bettse)
  - OFW: Fix ISO15693 stuck in wrong mode (by @RebornedBrain)
  - OFW: Fix MFUL PWD_AUTH command creation when 0x00 in password (by @GMMan)
  - OFW: Fix typo for `mf_classic_key_cahce_get_next_key()` function (by @luu176)
- OFW: U2F: Fix message digest memory leak (by @GMMan)
- OFW: JS: SDK workaround incorrect serial port handling by OS (by @portasynthinca3)
- OFW: FBT: Fix invalid path errors on Windows with UTF8 paths (by @Alex4386)

### Removed:
- NFC: Previous fix for ISO15693 stuck in wrong mode (#225)
  - Removes APIs `nfc_iso15693_detect_mode()`, `nfc_iso15693_force_1outof4()`, `nfc_iso15693_force_1outof256()`
