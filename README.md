<div align="center">

# asdf-typst [![Build](https://github.com/stephane-klein/asdf-typst/actions/workflows/build.yml/badge.svg)](https://github.com/stephane-klein/asdf-typst/actions/workflows/build.yml) [![Lint](https://github.com/stephane-klein/asdf-typst/actions/workflows/lint.yml/badge.svg)](https://github.com/stephane-klein/asdf-typst/actions/workflows/lint.yml)

[typst](https://github.com/typst/typst) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, [`xz`](https://en.wikipedia.org/wiki/XZ_Utils), and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add typst
# or
asdf plugin add typst https://github.com/stephane-klein/asdf-typst.git
```

typst:

```shell
# Show all installable versions
asdf list-all typst

# Install specific version
asdf install typst latest

# Set a version globally (on your ~/.tool-versions file)
asdf global typst latest

# Now typst commands are available
typst --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/stephane-klein/asdf-typst/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stéphane Klein](https://github.com/stephane-klein/)
