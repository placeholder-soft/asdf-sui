<div align="center">

# asdf-sui [![Build](https://github.com/placeholder-soft/asdf-sui/actions/workflows/build.yml/badge.svg)](https://github.com/placeholder-soft/asdf-sui/actions/workflows/build.yml) [![Lint](https://github.com/placeholder-soft/asdf-sui/actions/workflows/lint.yml/badge.svg)](https://github.com/placeholder-soft/asdf-sui/actions/workflows/lint.yml)

[sui](https://github.com/placeholder-soft/asdf-sui) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sui
# or
asdf plugin add sui https://github.com/placeholder-soft/asdf-sui.git
```

sui:

```shell
# Show all installable versions
asdf list-all sui

# Install specific version
asdf install sui latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sui latest

# Now sui commands are available
sui --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/placeholder-soft/asdf-sui/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zitao Xiong](https://github.com/placeholder-soft/)
