# homebrew-tap

Homebrew tap for [@alexremn](https://github.com/alexremn)'s tools.

## Available casks

| Tool | Install | What it does |
|------|---------|--------------|
| [finalizer-doctor](https://github.com/alexremn/finalizer-doctor) | `brew install alexremn/tap/finalizer-doctor` | Safely diagnose/clear finalizers on stuck-`Terminating` Kubernetes resources (`kubectl finalizer-doctor` / `kubectl fid`) |
| [keyspan](https://github.com/alexremn/keyspan) | `brew install alexremn/tap/keyspan` | Secret blast-radius graph — "if I rotate this credential, what breaks and who owns it?" |
| [kubectl-fieldlord](https://github.com/alexremn/kubectl-fieldlord) | `brew install alexremn/tap/kubectl-fieldlord` | Explain Server-Side Apply field ownership, drift, and clobber risk |

## How this tap is maintained

Casks under `Casks/` are generated and committed automatically by
[GoReleaser](https://goreleaser.com) from each project's release workflow on every
tagged release. Do not edit them by hand.
