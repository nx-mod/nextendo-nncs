# nextendo-nncs (nx-mod testing)

nx-mod's `testing` fork of [nextendo-nncs](https://github.com/NextendoNetwork/nextendo-nncs): Nintendo NAT-check (NCS/nncs) responder for the Nextendo private network.
Part of [nextendo-testing](https://github.com/nx-mod/nextendo-testing): the whole Nextendo Network, run on a LAN. Upstream's README is kept as [README.upstream.md](README.upstream.md).

## nx-mod changes

- NAT-check responders bind explicit local IPs instead of the wildcard.
- NAT probe readings compared only within the same round.

## Credits

nextendo-nncs is the work of the **Nextendo Network team** — https://nextendo.network. nx-mod only adds the changes above, for LAN testing. Nextendo is awesome.
