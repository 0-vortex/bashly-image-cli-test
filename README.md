<div align="center">
  <img src="https://raw.githubusercontent.com/0-vortex/0-vortex/main/static/logo.svg" width="50%">

# :cyclone: 0-vortex/bashly-image-cli-test :dna:

> CLI written in [bashly](https://bashly.dannyb.co) for image related functions.

[![Commits](https://img.shields.io/github/commit-activity/w/0-vortex/bashly-image-cli-test?style=flat)](https://github.com/0-vortex/bashly-image-cli-test/pulse)
[![Issues](https://img.shields.io/github/issues/0-vortex/bashly-image-cli-test.svg?style=flat)](https://github.com/0-vortex/bashly-image-cli-test/issues)
[![Releases](https://img.shields.io/github/v/release/0-vortex/bashly-image-cli-test.svg?style=flat)](https://github.com/0-vortex/bashly-image-cli-test/releases)

</div>

## 🚀 Setup

This project was setup using these commands:

```shell
bashly init
bashly add colors
bashly add settings
bashly add validations
bashly add completions
bashly add yaml
bashly add lib
bashly add hooks
bashly generate
```

## 📖 Prerequisites

In order to run the project we need the following software binaries installed on our development machines:

- [x] `docker>=20.10.12`
- [x] `bash>=4`
- [ ] `bashly>=1.0.4`
- [ ] `shfmt>=3.4.0`

Requirements not explicitly checked above are assumed to be met by `docker` containers:

```shell
alias bashly='docker run --rm --interactive --tty --volume "$PWD:/app" --user $(id -u):$(id -g) dannyben/bashly'
alias shfmt='docker run --rm --volume "$PWD:/mnt" mvdan/shfmt --case-indent --indent 2 --diff /mnt'
```

[//]: # (## 🖥️ Local development)

[//]: # (## 🤝 Contributing)

## 📝 License

CC BY-SA 4.0 © [TED Vortex](./LICENSE)
