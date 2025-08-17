# nixos-anywhere-examples

Checkout the [flake.nix](flake.nix) for examples tested on different hosters.

## Run nixos-anywhere

```bash
nix run nixpkgs#nixos-anywhere -- \
    --flake .#generic \
    --generate-hardware-config nixos-generate-config ./hardware-configuration.nix \
    root@192.168.0.10
```
