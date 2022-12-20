# IOTA Firefly wallet install and verify script

## Reads Firefly wallet install data from:
 - https://github.com/iotaledger/firefly

## Actions
- Read version, checksum, and PGP code signature from latest github release
- Download latest github release AppImage binary
- Compute SHA256 checksum of downloaded binary
- Verify calculated checksum against published github release page checksums
- On validation success, install AppImage to ~/Desktop
