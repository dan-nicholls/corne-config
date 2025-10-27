# ZMK Corne Config

A reproduceable firmware setup for my Corne (`crkbd`) keymap using `ZMK` and `nix`.

## Prerequisites

- `nix-shell` with flakes enabled.

## Usage

1. Start `nix` session

```sh
nix develop
```

1. Initialise libraries if its the first time runnning.

```sh
just init
```

1. Build keymaps in `./config`

```sh
just build all

// Build single board
just build <target>
just build corne // eg. build corne
```

## Resources

- [ZMK Documentation](https://zmk.dev/docs)
- [urob's ZMK Config](https://github.com/urob/zmk-config)
- [Pinned zephyr-nix commit](https://github.com/nix-community/zephyr-nix/commit/b614ffaa1343beacaca254213451186af10e88f6)
- [Miryoku keymap](https://github.com/manna-harbour/miryoku)
- [KeymapDB](https://keymapdb.com/)
- [markstos Corne layout](https://mark.stosberg.com/markstos-corne-3x5-1-keyboard-layout/)
