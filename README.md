# homebrew-tap

Homebrew casks for [proto-tap](https://github.com/proto-tap) tools.

## Usage

```bash
brew install --cask proto-tap/tap/sql-tap
brew install --cask proto-tap/tap/http-tap
brew install --cask proto-tap/tap/grpc-tap
```

To install and upgrade by name (e.g., `brew install --cask sql-tap`, `brew upgrade`), tap and trust it first:

```bash
brew tap proto-tap/tap
brew trust proto-tap/tap
```

Casks are published by GoReleaser on each release.
