# ESX Resource Template

[![CI](https://github.com/Mlcastor/esx_resource_template/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Mlcastor/esx_resource_template/actions/workflows/ci.yml)
[![Latest Release](https://img.shields.io/github/v/release/Mlcastor/esx_resource_template?sort=semver)](https://github.com/Mlcastor/esx_resource_template/releases)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)

>A batteries-included boilerplate every new **ESX/FiveM** script starts from.

## Features

* Opinionated project layout (`client/`, `server/`, `shared/`)
* **Stylua + Luacheck** pre-configured
* GitHub Actions CI (lint, format, smoke test)
* Automated semantic releases via **Release Please**
* `init-resource.sh` scaffold script – instantly duplicate & rename
* Community files: issue/PR templates, Code of Conduct, Contributing guide

## Quick start

```bash
# 1. Generate a new resource from this template
./init-resource.sh esx_mynewscript "Your Name" "Fancy description"

# 2. Develop
cd esx_mynewscript
make lint   # luacheck
make format # stylua

# 3. Commit using Conventional Commits, push → CI opens release PR
```

### Directory structure

```
├── client/
│   └── main.lua
├── server/
│   └── main.lua
├── shared/
├── fxmanifest.lua
└── README.md
```

## Using the template manually

1. Click **Use this template** on GitHub
2. Run `./init-resource.sh <name>`
3. Follow the CONTRIBUTING checklist and start coding ✨

## Documentation & help

* [CONTRIBUTING.md](CONTRIBUTING.md) – code style & release flow
* [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) – community expectations
* Open a [📝 question](https://github.com/Mlcastor/esx_resource_template/issues/new?template=question.md) if you're stuck

## License

Distributed under the **GPL-3.0** license. See [`LICENSE`](LICENSE).