# arc-reth

Circle's fork of [reth](https://github.com/paradigmxyz/reth) for
[Arc](https://www.arc.io/).

This repository holds upstream reth releases plus backports of upstream fixes
that are already public. It lets [arc-node](https://github.com/circlefin/arc-node)
use a patched reth release when an upstream fix is not yet in a reth release
for the reth version that arc-node uses.

This repository does not add features. Each release branch is an upstream
reth release plus cherry-picked upstream commits only.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security

See [SECURITY.md](SECURITY.md). Do not file public issues for security
vulnerabilities.

## License

reth is licensed under either of the following, at your option:

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE))
- MIT License ([LICENSE-MIT](LICENSE-MIT))

This repository keeps the upstream licenses without change. The code is
Copyright 2022-2026 Reth Contributors. Backported commits keep their original
authors.
