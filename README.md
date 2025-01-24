<div align="center">

# asdf-tgenv [![Build](https://github.com/carlduevel/asdf-tgenv/actions/workflows/build.yml/badge.svg)](https://github.com/carlduevel/asdf-tgenv/actions/workflows/build.yml) [![Lint](https://github.com/carlduevel/asdf-tgenv/actions/workflows/lint.yml/badge.svg)](https://github.com/carlduevel/asdf-tgenv/actions/workflows/lint.yml)


[tgenv](https://github.com/4ng31/asdf-tgenv.git) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# BASED ON THE [asdf-tfenv plugin](https://github.com/carlduevel/asdf-tgenv)!
 

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add tgenv
# or
asdf plugin add tgenv https://github.com/4ng31/asdf-tgenv.git
```

tgenv:

```shell
# Show all installable versions
asdf list-all tgenv

# Install specific version
asdf install tgenv latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tgenv latest

# Now tgenv commands are available
tgenv
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

As of version 0.4.0 there is no ARM Mac build of tgenv.
See [this](https://github.com/asdf-vm/asdf/issues/834#issuecomment-924682825) workaround to install the amd64 version instead.
This will then work on ARM due to [Rosetta 2](https://en.wikipedia.org/wiki/Rosetta_(software)#Rosetta_2). 

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/4ng31/asdf-tgenv/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carl Düvel](https://github.com/carlduevel/)
