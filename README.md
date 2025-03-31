<div align="center">

# asdf-pwru [![Build](https://github.com/sayboras/asdf-pwru/actions/workflows/build.yml/badge.svg)](https://github.com/sayboras/asdf-pwru/actions/workflows/build.yml) [![Lint](https://github.com/sayboras/asdf-pwru/actions/workflows/lint.yml/badge.svg)](https://github.com/sayboras/asdf-pwru/actions/workflows/lint.yml)

[pwru](https://github.com/cilium/pwru) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add pwru
# or
asdf plugin add pwru https://github.com/sayboras/asdf-pwru.git
```

pwru:

```shell
# Show all installable versions
asdf list-all pwru

# Install specific version
asdf install pwru latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pwru latest

# Now pwru commands are available
pwru --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sayboras/asdf-pwru/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tam Mach](https://github.com/sayboras/)
