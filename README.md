# executable.yazi

Execute `chmod +x` on the selected files to change their mode. This plugin is only available on Unix platforms since it relies on [`chmod(2)`](https://man7.org/linux/man-pages/man2/chmod.2.html).


## Installation

```sh
git clone https://git@github.com/tasnimAlam/executable.git ~/.config/yazi/plugins/
```

## Usage

Add this to your `~/.config/yazi/keymap.toml`:

```toml
[[manager.prepend_keymap]]
on   = [ "*" ]
run  = "plugin executable"
desc = "Make selected files executable"
```

## License

This plugin is MIT-licensed. For more information check the [LICENSE](LICENSE) file.

