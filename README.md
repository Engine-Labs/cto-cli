# cto

`cto` is the command-line interface for [cto.new](https://cto.new) — an AI-powered engineering agent in your terminal.

## Install

### macOS — Homebrew (recommended)

```sh
brew install engine-labs/cto/cto
```

### macOS / Linux — curl

```sh
curl -fsSL cto.new/install | bash
```

### Windows — PowerShell

```powershell
irm https://cto.new/install.ps1 | iex
```

Then `cd` into any repository and run:

```sh
cto
```

The first launch opens your browser to log you in via cto.new; subsequent launches are silent. Use `cto login` to re-authenticate or switch accounts, or `/cto-login` from inside an opencode session.

## Updating

```sh
cto upgrade
```

If you installed via Homebrew, use `brew upgrade cto` instead — `cto upgrade` will detect the brew-managed binary and refuse rather than overwrite it.

## Help & community

For help, bug reports, or feature requests, join the Discord: <https://discord.gg/cto>.

## License

Proprietary. See [LICENSE](./LICENSE). Embedded third-party components retain their original licenses; run `cto --licenses` for the full notices.
