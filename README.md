# awg-manager-dev

Dev/testing channel for [awg-manager](https://github.com/hoaxisr/awg-manager) IPK packages.

## Usage

Replace the stable feed URL with this one in your opkg configuration:

```
src/gz awg-manager-dev https://hoaxisr.github.io/awg-manager-dev/{arch}-kn
```

Where `{arch}` is one of: `mipsel-3.4`, `mips-3.4`, `aarch64-3.10`.

## Warning

These are pre-release builds for testing. They may be unstable.
Use the [stable channel](https://github.com/hoaxisr/entware-repo) for production.
