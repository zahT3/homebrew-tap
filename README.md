# zahT3 homebrew-tap

```bash
brew install zahT3/tap/ip-please
```

## Formulas

- [`ip-please`](Formula/ip-please.rb) — egress-identity auditor and fail-closed circuit breaker for AI accounts (macOS)

After installing, run the system-side setup once (writes `/etc`, loads launchd, needs sudo):

```bash
sudo "$(brew --prefix ip-please)/libexec/install.sh"
```
