# homebrew-tap

Homebrew tap for [finalizer-doctor](https://github.com/alexremn/finalizer-doctor) —
a safe stuck-`Terminating` doctor for Kubernetes (`kubectl finalizer-doctor`).

## Install

```bash
brew install alexremn/tap/finalizer-doctor
```

This installs both `kubectl-finalizer_doctor` and `kubectl-fid` on your `PATH`, so
`kubectl finalizer-doctor` and `kubectl fid` work immediately.

## How this tap is maintained

`Formula/finalizer-doctor.rb` is generated and committed automatically by
[GoReleaser](https://goreleaser.com) from the finalizer-doctor release workflow on
each tagged release. Do not edit it by hand.
