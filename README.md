# asdf-sd
[sd](https://github.com/chmln/sd) plugin for the [asdf version manager](https://asdf-vm.com).

`sd` is an intuitive find & replace CLI tool, an alternative to `sed`.

## Contents
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies
**Required:**
- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html)
- `git`: for listing versions
- `unzip`: for Windows installations (if using on Windows/WSL)

## Install
Plugin:
```shell
asdf plugin add sd https://github.com/AxlER8R/asdf-sd.git
```

sd:
```shell
# Show all installable versions
asdf list all sd

# Install specific version
asdf install sd 1.0.0

# Install latest version
asdf install sd latest

# Set a version globally (on your ~/.tool-versions file)
asdf set --home sd latest

# Now sd commands are available
sd --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

## Contributing
Contributions of any kind welcome! See the [contributing guide](CONTRIBUTE.md).

## License
See [LICENSE](LICENSE) © [AxlER8R](https://github.com/AxlER8R/)
