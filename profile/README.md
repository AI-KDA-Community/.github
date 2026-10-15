# Welcome to AI-KDA-Community

Kadena AI ecosystem tools and releases.

## What We Build

AI Focused Development ( Community base effort ) For The Kadena Chainweb blockchain.


## Current Repositorys Of Interest Include





### Direct Download

Binaries: https://github.com/AI-KDA-Community/releases

## Getting Help

Open an issue in the relevant repository.

## For Developers: Bootstrap Your Own Org

Running your own org and want the same structure? The tool we use to set this up is public:

**[homebrew-tap-app](https://github.com/AI-KDA-Community/homebrew-tap-app)** — a single script that scaffolds:

- **`.github`** — org profile README + shared community health files
- **`releases`** — central hub where every tagged build lands
- **`homebrew-tap`** — package manager formulae, auto-bumped by CI
- **Source repos** — one per project, with branch layout for project work
- **Release workflow** — GoReleaser config + GitHub Actions, tag → build → publish → formula bump, fully automated
- **Release schedule** — driven by tags, so `git tag vX.Y.Z && git push --tags` is the whole workflow

Clone it, point it at your org, run `./run.sh`. Safe to re-run.
