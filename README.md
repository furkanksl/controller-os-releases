# ControllerOS Releases

Official update repository for [ControllerOS](https://controlleros.furkanksl.com) — remap your game controller to keyboard & mouse on macOS.

## Download

Get the latest version at **[controlleros.furkanksl.com](https://controlleros.furkanksl.com)**

## How Updates Work

ControllerOS checks for updates automatically on launch. The app fetches `update.json` from the latest GitHub release to determine if a newer version is available. If there is one, you'll be prompted to download and install it directly from the app.

## Release Assets

Each release includes:

| File | Description |
|------|-------------|
| `controller-os.app.tar.gz` | Universal macOS app (Apple Silicon + Intel) |
| `controller-os.app.tar.gz.sig` | Update signature for integrity verification |
| `update.json` | Version manifest used by the in-app updater |

## Verifying Downloads

All update artifacts are signed with a Tauri update signature. The app verifies signatures automatically before installing any update.

## Links

- **Website:** [controlleros.furkanksl.com](https://controlleros.furkanksl.com)
