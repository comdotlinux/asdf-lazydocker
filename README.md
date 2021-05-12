<div align="center">

# asdf-lazydocker ![Build](https://github.com/comdotlinux/asdf-lazydocker/workflows/Build/badge.svg) ![Lint](https://github.com/comdotlinux/asdf-lazydocker/workflows/Lint/badge.svg)

[lazydocker](https://github.com/jesseduffield/lazydocker/blob/master/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lazydocker
# or
asdf plugin add lazydocker https://github.com/comdotlinux/asdf-lazydocker.git
```

lazydocker:

```shell
# Show all installable versions
asdf list-all lazydocker

# Install specific version
asdf install lazydocker latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lazydocker latest

# Now lazydocker commands are available
lazydocker --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/comdotlinux/asdf-lazydocker/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Guruprasad Kulkarni](https://github.com/comdotlinux/)
