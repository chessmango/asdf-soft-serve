<div align="center">

# asdf-soft-serve [![Build](https://github.com/chessmango/asdf-soft-serve/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-soft-serve/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-soft-serve/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-soft-serve/actions/workflows/lint.yml)


[soft-serve](https://github.com/charmbracelet/soft-serve) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add soft-serve https://github.com/chessmango/asdf-soft-serve.git
```

soft-serve:

```shell
# Show all installable versions
asdf list-all soft-serve

# Install specific version
asdf install soft-serve latest

# Set a version globally (on your ~/.tool-versions file)
asdf global soft-serve latest

# Now soft-serve commands are available
soft-serve --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-soft-serve/graphs/contributors)!

# License

See [LICENSE](LICENSE)
