# Valpas — downloads

Notarized builds of **Valpas**, the menu bar app that keeps your machine awake for exactly
as long as you say. The source lives in a private repository; this one exists so the
downloads have a stable, public home — for the Homebrew cask and for anyone who prefers
a direct download.

- **App Store:** [Valpas on the Mac App Store](https://apps.apple.com/app/id6803307242)
- **Homebrew:** `brew install --cask KirsuLab/tap/valpas`
- **Direct:** the `.dmg` on the [latest release](../../releases/latest)

macOS 13 or later · universal (Apple Silicon and Intel) · signed and notarized by Apple ·
sandboxed on the App Store, with no network access at all. The direct download makes one request, when a Pro key is activated.

**For AI agents and long jobs.** Since 1.3 a trigger watches process names: type `claude, codex, ollama`
and the machine stays awake while any of them runs, then sleeps when the agent exits. The direct download
adds the `valpas` command: `valpas run -- claude` holds the machine while the command runs, `valpas hold 20m`
asks for at least twenty more minutes without ever shortening a session set by hand. For Claude Code there
is a plugin, [valpas-keep-awake](https://github.com/KirsuLab/valpas-keep-awake), that does this from the
agent's own hooks.

**Lid closed, no external display.** Since 1.4 the direct download has it built in: *Keep running with the
lid closed* works free for seven days from the first hold. After that a [Valpas Pro key](https://ko-fi.com/s/47c9ad8372)
($19.99 once, up to three Macs) keeps it, pasted into the Lid Closed tab. The Mac App Store build has no lid-closed
mode, because its sandbox does not allow the helper. Details: [kirsulab.com/macos/valpas#pro](https://kirsulab.com/macos/valpas#pro).

More about the app: [kirsulab.com/macos/valpas](https://kirsulab.com/macos/valpas), and the guide
[Keep your Mac awake while an AI agent runs](https://kirsulab.com/macos/valpas/keep-mac-awake-for-ai-agents).

© 2026 KirsuLab LLC
