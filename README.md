# homebrew-apps

Homebrew tap for antavik's applications.

## Apps

| App | Install |
|-----|---------|
| [glinet-cli](https://github.com/antavik/glinet-cli) | `brew install antavik/apps/glinet-cli` |

Using the full name trusts only the formula, not the whole tap.

## How it works

Formulas in `Formula/` are generated and pushed automatically by each app's
release workflow. For glinet-cli, the
[release workflow](https://github.com/antavik/glinet-cli/actions/workflows/release.yml)
updates `Formula/glinet-cli.rb` after every release: prebuilt binaries for
macOS and Linux (arm64/amd64) with SHA-256 checksums taken from the release's
`checksums.txt`. Do not edit generated formulas by hand — changes are
overwritten on the next release.

Casks for GUI apps can live in `Casks/` (none yet).
