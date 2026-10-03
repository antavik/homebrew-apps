# homebrew-tap

Homebrew tap for [glinet-cli](https://github.com/antavik/glinet-cli).

## Usage

```sh
brew install antavik/tap/glinet-cli
```

Using the full name trusts only this formula, not the whole tap.

## How it works

`Formula/glinet-cli.rb` is generated and pushed automatically by the
[glinet-cli release workflow](https://github.com/antavik/glinet-cli/actions/workflows/release.yml)
after every release: prebuilt binaries for macOS and Linux (arm64/amd64) with
SHA-256 checksums taken from the release's `checksums.txt`. Do not edit the
formula by hand — changes are overwritten on the next release.

The formula appears here after the first release (`v0.1.0`).
