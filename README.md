<div align="center">

# asdf-goconvey [![Build](https://github.com/therounds-contrib/asdf-goconvey/actions/workflows/build.yml/badge.svg)](https://github.com/therounds-contrib/asdf-goconvey/actions/workflows/build.yml) [![Lint](https://github.com/therounds-contrib/asdf-goconvey/actions/workflows/lint.yml/badge.svg)](https://github.com/therounds-contrib/asdf-goconvey/actions/workflows/lint.yml)


[goconvey](https://smartystreets.github.io/goconvey/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add goconvey
# or
asdf plugin add goconvey https://github.com/therounds-contrib/asdf-goconvey.git
```

goconvey:

```shell
# Show all installable versions
asdf list-all goconvey

# Install specific version
asdf install goconvey latest

# Set a version globally (on your ~/.tool-versions file)
asdf global goconvey latest

# Now goconvey commands are available
goconvey -help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/therounds-contrib/asdf-goconvey/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Boondoc Technologies Inc.](https://therounds.com/)
