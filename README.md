<div align="center">

# asdf-uds-cli [![Build](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/build.yml/badge.svg)](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/build.yml) [![Lint](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/lint.yml)

Unofficial [uds-cli](https://github.com/defenseunicorns/uds-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# About

This is an [asdf](https://asdf-vm.com) plugin for [uds-cli](https://github.com/defenseunicorns/uds-cli). It is not officially supported by the UDS team, but has been in use for long enough to be considered robust and stable.

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

## asdf

`asdf` can be installed by following the instructions [here](https://asdf-vm.com/guide/getting-started.html).

## Plugin

```shell
asdf plugin add uds-cli https://github.com/defenseunicorns/asdf-uds-cli.git
```

## uds-cli

```shell
# Show all installable versions
asdf list-all uds-cli

# Install specific version
asdf install uds-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global uds-cli latest

# Now uds commands are available
uds --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/defenseunicorns/asdf-uds-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [defenseunicorns](https://github.com/defenseunicorns/)
