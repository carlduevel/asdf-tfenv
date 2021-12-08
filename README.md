<div align="center">

# asdf-tfenv [![Build](https://github.com/carlduevel/asdf-tfenv/actions/workflows/build.yml/badge.svg)](https://github.com/carlduevel/asdf-tfenv/actions/workflows/build.yml) [![Lint](https://github.com/carlduevel/asdf-tfenv/actions/workflows/lint.yml/badge.svg)](https://github.com/carlduevel/asdf-tfenv/actions/workflows/lint.yml)


[tfenv](https://github.com/cloudposse/tfenv) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

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
asdf plugin add tfenv
# or
asdf plugin add tfenv https://github.com/carlduevel/asdf-tfenv.git
```

tfenv:

```shell
# Show all installable versions
asdf list-all tfenv

# Install specific version
asdf install tfenv latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfenv latest

# Now tfenv commands are available
tfenv
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/carlduevel/asdf-tfenv/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carl Düvel](https://github.com/carlduevel/)
