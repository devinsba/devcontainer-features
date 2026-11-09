# devcontainer-features

Custom [dev container features](https://containers.dev/implementors/features/). Each feature lives in
`src/<id>/` with a `devcontainer-feature.json` and an `install.sh`.

## Features

| Feature | Copied from |
| --- | --- |
| `fnm-node` | [devcontainers/features `node`](https://github.com/devcontainers/features/tree/main/src/node) |
| `pyenv-python` | [devcontainers/features `python`](https://github.com/devcontainers/features/tree/main/src/python) |

Copied under the MIT license (see `LICENSE`); the copies are unmodified apart from their ids and
documentation URLs, with tests in `test/<id>/`. Published to `ghcr.io/devinsba/devcontainer-features/<id>`.
