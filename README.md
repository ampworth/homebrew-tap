# Ampworth Homebrew tap

Install the [ampworth command line](https://github.com/ampworth/cli): UK solar
PV and heat pump calculators that follow the published MCS standards, the
guides that explain them, and a local MCP server for AI assistants.

```sh
brew install ampworth/tap/ampworth
```

Upgrade with `brew upgrade ampworth`.

The cask in `Casks/` is updated automatically when a new version of the CLI is
released, so there's nothing to edit here by hand.

The binaries aren't signed with an Apple developer certificate, so the cask
removes macOS's quarantine flag from the `ampworth` binary after installing it.
Without that, macOS refuses to run it. If you'd rather not, download the binary
from the [releases page](https://github.com/ampworth/cli/releases) instead.
