# homebrew-tap

Homebrew tap for DevOps House CLI tools.

Add the tap:

```bash
brew tap devopshouse/tap
```

List available packages:

```bash
brew search devopshouse/tap
```

Install `tmswitch`:

```bash
brew install devopshouse/tap/tmswitch
```

If a project is published as a cask instead of a formula, install it with:

```bash
brew install --cask devopshouse/tap/<name>
```

This repository is updated automatically by GoReleaser from source repositories,
including:

- [`devopshouse/tmswitch`](https://github.com/devopshouse/tmswitch)
