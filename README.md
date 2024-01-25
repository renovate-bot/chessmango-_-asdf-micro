<div align="center">

# asdf-micro [![Build](https://github.com/chessmango/asdf-micro/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-micro/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-micro/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-micro/actions/workflows/lint.yml)

[micro](https://github.com/zyedidia/micro) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add micro
# or
asdf plugin add micro https://github.com/chessmango/asdf-micro.git
```

micro:

```shell
# Show all installable versions
asdf list-all micro

# Install specific version
asdf install micro latest

# Set a version globally (on your ~/.tool-versions file)
asdf global micro latest

# Now micro commands are available
micro --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-micro/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Owen Valentine](https://github.com/chessmango/)
