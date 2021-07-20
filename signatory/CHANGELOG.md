# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.23.0 (2021-07-20)
### Changed
This release is effectively a complete rewrite of Signatory with a brand-new
API, and as such contains changes too numerous to document. For that reason,
we are pushing the reset button on the changelog.

It still provides the same original set of functionality, including ECDSA and
Ed25519 signatures, but temporarily drops support for P-384 and hardware-backed
digital signature providers.

The plan is to eventually add this functionality back. The new implementation
is fundamentally built on the same original codebase, but refactored and
extracted into other Rust crates. Given that, we hope to achieve feature
parity with the original implementation quickly.