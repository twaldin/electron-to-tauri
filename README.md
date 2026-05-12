# electron-to-tauri

A small collection of popular Electron-style apps rebuilt as simple Tauri webview
wrappers.

These apps intentionally start as thin webview shells around the official web
apps. No full desktop-app functionality or feature parity is promised. Voice,
screen sharing, notifications, tray behavior, deep links, and other native
features may need per-app work or may be limited by the platform webview.

## Apps

- Discord: `https://discord.com/app`
- Slack: `https://app.slack.com/client`

## Run

Discord:

```sh
cargo run
```

Slack:

```sh
cd apps/tauri-slack
cargo run
```
