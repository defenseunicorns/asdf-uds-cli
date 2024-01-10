<div align="center">

# asdf-uds-cli [![Build](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/build.yml/badge.svg)](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/build.yml) [![Lint](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/defenseunicorns/asdf-uds-cli/actions/workflows/lint.yml)

[uds-cli](https://github.com/defenseunicorns/uds-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-uds-cli](#asdf-uds-cli--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add uds-cli
# or
asdf plugin add uds-cli https://github.com/defenseunicorns/asdf-uds-cli.git
```

uds-cli:

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

See [LICENSE](LICENSE) © [zack](https://github.com/defenseunicorns/)
