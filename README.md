<div align="center">

# asdf-fzf [![Build](https://github.com/grimm26/asdf-fzf/actions/workflows/build.yml/badge.svg)](https://github.com/grimm26/asdf-fzf/actions/workflows/build.yml) [![Lint](https://github.com/grimm26/asdf-fzf/actions/workflows/lint.yml/badge.svg)](https://github.com/grimm26/asdf-fzf/actions/workflows/lint.yml)

[fzf](https://junegunn.github.io/fzf/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add fzf
# or
asdf plugin add fzf https://github.com/grimm26/asdf-fzf.git
```

fzf:

```shell
# Show all installable versions
asdf list-all fzf

# Install specific version
asdf install fzf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fzf latest

# Now fzf commands are available
fzf --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/grimm26/asdf-fzf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mark Keisler](https://github.com/grimm26/)
