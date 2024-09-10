<div align="center">

# asdf-esc [![Build](https://github.com/fxsalazar/asdf-esc/actions/workflows/build.yml/badge.svg)](https://github.com/fxsalazar/asdf-esc/actions/workflows/build.yml) [![Lint](https://github.com/fxsalazar/asdf-esc/actions/workflows/lint.yml/badge.svg)](https://github.com/fxsalazar/asdf-esc/actions/workflows/lint.yml)

[esc](https://github.com/fxsalazar/asdf-esc) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add esc
# or
asdf plugin add esc https://github.com/fxsalazar/asdf-esc.git
```

esc:

```shell
# Show all installable versions
asdf list-all esc

# Install specific version
asdf install esc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global esc latest

# Now esc commands are available
esc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/fxsalazar/asdf-esc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Felix Salazar](https://github.com/fxsalazar/)
