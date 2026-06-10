# homebrew-kzero

Homebrew tap for [kzero](https://github.com/hrodrig/kzero) — declarative Kubernetes workload **down** / **up** / **reset** pipelines from YAML.

Same pattern as **[homebrew-pgwd](https://github.com/hrodrig/homebrew-pgwd)**: **`Casks/kzero.rb`** is generated and pushed by **GoReleaser** on each [kzero release tag](https://github.com/hrodrig/kzero/releases) (`HOMEBREW_TAP_TOKEN` on the **kzero** repo).

## Install

```bash
brew install hrodrig/kzero/kzero
```

Works on **macOS** and **Linux** (Homebrew on Linux). Installs the **`kzero`** binary and **`man kzero`** (from the release tarball).

## Links

- **Project:** [github.com/hrodrig/kzero](https://github.com/hrodrig/kzero)
- **Operator docs (bastion, cron, kind e2e):** [kzero-selfhosted](https://github.com/hrodrig/kzero-selfhosted)
- **Releases:** [kzero releases](https://github.com/hrodrig/kzero/releases)

## Maintainers

- **Do not edit `Casks/kzero.rb` by hand** — the next kzero tag overwrites it.
- If your local clone only shows this README, run **`git pull`** (GoReleaser commits land on **`main`** after each tag).
- If the tap did not update after a release, check the **kzero** Release workflow and **`HOMEBREW_TAP_TOKEN`** (PAT with **`contents:write`** on this repo).
