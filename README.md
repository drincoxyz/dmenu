# dmenu

This is my fork of the [dynamic menu](https://tools.suckless.org/dmenu), one of many [suckless](https://suckless.org) software.

## Installing

```sh
make && sudo make install && make clean
```

## Patches

This build of dmenu uses the following patches (in order of when they were applied, from oldest to newest):

+ [password](https://tools.suckless.org/dmenu/patches/password) - Adds a flag to mask user input, suitable for sensitive information like passwords.
