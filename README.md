# electron-to-tauri

My collection of popular Electron-style apps running in Tauri webviews.

These are intentionally thin wrappers around the official web apps. No full
desktop-app functionality or feature parity is promised. Voice, screen sharing,
notifications, tray behavior, deep links, and other native features may need
per-app work or may be limited by the platform webview.

## Apps

- Discord: `apps/tauri-discord` wraps `https://discord.com/app`
- Slack: `apps/tauri-slack` wraps `https://app.slack.com/client`

## Run Locally

```sh
cargo run -p tauri-discord
cargo run -p tauri-slack
```

## Releases

Tagged releases build downloadable desktop app bundles with GitHub Actions:

```sh
git tag v0.1.0
git push origin v0.1.0
```

The release workflow builds Discord and Slack wrappers for macOS, Windows, and
Linux, then uploads the installers to the GitHub Release.
