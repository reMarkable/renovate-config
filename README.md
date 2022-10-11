# Renovate configuration defaults

Here you'll find the Renovate default configuration for reMarkable.

## Getting started

To start using renovate in your repo you should follow the instructions in [cloud-shared-services](https://github.com/reMarkable/cloud-shared-services/blob/main/docs/Renovate.md), which will add renovate bot and open a PR to start inheriting from this repo by default.

To inherit configuration from this repo, your `renovate.json` should contain:

```json
{
  "extends": ["local>reMarkable/renovate-config"]
}
```

## pre-commit

This repo has [pre-commit hooks](./.pre-commit-config.yaml) that helps us keep consistent and avoid nits in reviews.

```sh
brew install pre-commit  # mac os
pip install -U pre-commit  # pyenv
pre-commit install
```
