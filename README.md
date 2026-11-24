# zahT3/tap

Homebrew formulae for zahT3's tools.

```sh
brew install zahT3/tap/hotseat
brew install zahT3/tap/ip-please
```

## Formulas

- [Hotseat](https://github.com/zahT3/hotseat): Claude account switcher for macOS. The formula builds the CLI and the menu bar app from source; after installing, copy the app with `mkdir -p ~/Applications && cp -R "$(brew --prefix)/opt/hotseat/Hotseat.app" ~/Applications/`.
- [ip-please](https://github.com/zahT3/ip-please): egress-identity auditor and fail-closed circuit breaker for AI accounts on macOS.
  After installing, run the system-side setup once (writes `/etc`, loads launchd, needs sudo):

  ```sh
  sudo "$(brew --prefix ip-please)/libexec/install.sh"
  ```
