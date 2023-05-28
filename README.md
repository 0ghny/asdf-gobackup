<div align="center">

# asdf-gobackup [![Build](https://github.com/0ghny/asdf-gobackup/actions/workflows/build.yml/badge.svg)](https://github.com/0ghny/asdf-gobackup/actions/workflows/build.yml) [![Lint](https://github.com/0ghny/asdf-gobackup/actions/workflows/lint.yml/badge.svg)](https://github.com/0ghny/asdf-gobackup/actions/workflows/lint.yml)


[gobackup](https://github.com/huacnlee/gobackup) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-gobackup  ](#asdf-gobackup--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- **Optional**: `ASDF_GOBACKUP_OVERWRITE_ARCH` if present you can specify arch to download an specific one.

# Install

Plugin:

```shell
asdf plugin add gobackup
# or
asdf plugin add gobackup https://github.com/0ghny/asdf-gobackup.git
```

gobackup:

```shell
# Show all installable versions
asdf list-all gobackup

# Install specific version
asdf install gobackup latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gobackup latest

# Now gobackup commands are available
gobackup --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/0ghny/asdf-gobackup/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [0ghny](https://github.com/0ghny/)
