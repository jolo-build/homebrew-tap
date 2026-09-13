# Jolo Homebrew tap

Install [Jolo](https://jolo.build) — a desktop app and CLI for working with coding agents — with Homebrew.

## CLI

```sh
brew install jolo-build/tap/jolo-cli
```

Works on macOS (Apple Silicon and Intel) and Linux (ARM64 and x64). The formula bundles Jolo's own runtime; no other dependencies are needed.

## Desktop app (macOS)

```sh
brew install --cask jolo-build/tap/jolo
```

Or tap first, then install by name:

```sh
brew tap jolo-build/tap
brew install jolo-cli
brew install --cask jolo
```

## Notes

- The desktop app is currently ad-hoc signed and not Apple-notarized; macOS may ask you to confirm opening it on first launch.
- Report issues in the [main repository](https://github.com/jolo-build/jolo/issues). This tap's update workflow checks the latest stable Jolo release every 30 minutes and can also be run manually from Actions. GitHub may delay scheduled runs. It uses the built-in repository token; no personal token is required.
