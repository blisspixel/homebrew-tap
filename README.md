# Homebrew tap for recon

This tap publishes the Homebrew formula for
[recon-tool](https://github.com/blisspixel/recon), a passive,
zero-credential domain-intelligence CLI and MCP server.

## Install

```bash
brew install blisspixel/tap/recon
```

Then run `recon --help` or `recon <domain>`. Upgrade with
`brew upgrade recon`; remove with `brew uninstall recon`.

## What this installs

`recon-tool` from PyPI into an isolated virtualenv, with the `recon`
command linked onto your PATH. The formula pins each release sdist by
`url` and `sha256`; runtime dependencies install from PyPI at build
time.

The canonical formula source lives in the main repository at
[`packaging/homebrew/recon.rb`](https://github.com/blisspixel/recon/blob/main/packaging/homebrew/recon.rb)
and is mirrored here per release. See the main project for
documentation, issues, and the release process.
