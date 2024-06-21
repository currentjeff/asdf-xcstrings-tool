<div align="center">

# asdf-xcstrings-tool [![Build](https://github.com/currentjeff/asdf-xcstrings-tool/actions/workflows/build.yml/badge.svg)](https://github.com/currentjeff/asdf-xcstrings-tool/actions/workflows/build.yml) [![Lint](https://github.com/currentjeff/asdf-xcstrings-tool/actions/workflows/lint.yml/badge.svg)](https://github.com/currentjeff/asdf-xcstrings-tool/actions/workflows/lint.yml)

[xcstrings-tool](https://github.com/currentjeff/asdf-xcstrings-tool) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

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
asdf plugin add xcstrings-tool
# or
asdf plugin add xcstrings-tool https://github.com/currentjeff/asdf-xcstrings-tool.git
```

xcstrings-tool:

```shell
# Show all installable versions
asdf list-all xcstrings-tool

# Install specific version
asdf install xcstrings-tool latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcstrings-tool latest

# Now xcstrings-tool commands are available
xcstrings-tool --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/currentjeff/asdf-xcstrings-tool/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jeff Moran](https://github.com/currentjeff/)
