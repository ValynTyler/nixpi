# Usage
build the image:
```bash
nix  --experimental-features 'nix-command flakes' build '.#nixosConfigurations.bramble-test-5.config.system.build.sdImage'
```

# Resources
- https://wiki.nixos.org/wiki/NixOS_on_ARM/Raspberry_Pi_5
- https://github.com/NixOS/nixpkgs/issues/260754#issuecomment-2501839916
