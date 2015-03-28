# config-wrap
Forces config and rc files for tools into `$XDG_CONFIG_HOME` instead of `$HOME`

Tired of programs littering your `$HOME` dir with config files? config-wrap to the rescue! Just create an alias prefixing the command with config-wrap, eg `alias='config-wrap foo'`, and config-wrap will automatically create a directory named `foo` in `$XDG_CONFIG_HOME` and force the foo commad to put it's config files there.
