# Changelog

## 1.0.0 (2024-05-13)


### Features

* add sgx input file lock to avoid concurrency problem ([9df1473](https://github.com/d1onys1us/raiko/commit/9df147394aa5e2c48a92364fcc037191faa914fd))
* batch get 256 history headers ([#95](https://github.com/d1onys1us/raiko/issues/95)) ([fd3434a](https://github.com/d1onys1us/raiko/commit/fd3434aa72766e9cb0a74e20a2bfe784743ebbe2))
* **raiko:** ci use sgx hw ([#175](https://github.com/d1onys1us/raiko/issues/175)) ([a40be21](https://github.com/d1onys1us/raiko/commit/a40be21d33d94414e4dc6259e17939785be69204))
* **raiko:** ci use sgx hw ([#175](https://github.com/d1onys1us/raiko/issues/175)) ([b7c44de](https://github.com/d1onys1us/raiko/commit/b7c44dedb784b39df9cbd7c87277f8355fa2fd50))
* **raiko:** enable kzg blob check ([#148](https://github.com/d1onys1us/raiko/issues/148)) ([9865b4c](https://github.com/d1onys1us/raiko/commit/9865b4cb91a56cbf0678d494cbea624f6ef0b067))
* **raiko:** generalized build pipeline for ZkVMs guests ([#133](https://github.com/d1onys1us/raiko/issues/133)) ([9cebd36](https://github.com/d1onys1us/raiko/commit/9cebd36a44c7243195b9cc1ef72ef2e949157dc1))
* **raiko:** install script + makefile CI integration ([#159](https://github.com/d1onys1us/raiko/issues/159)) ([a6c1095](https://github.com/d1onys1us/raiko/commit/a6c10953326b449127f6dcda2b92d2b1747c7f2d))
* **raiko:** raiko object ([#149](https://github.com/d1onys1us/raiko/issues/149)) ([c4215bd](https://github.com/d1onys1us/raiko/commit/c4215bde45675d57e7a16f32107146b3b9756e75))
* **raiko:** run general tests on all targets ([#164](https://github.com/d1onys1us/raiko/issues/164)) ([27b0bee](https://github.com/d1onys1us/raiko/commit/27b0beeaace5b93d1d32ac9b13da0722793fafeb))
* use batch api instead of customize api for history headers ([49d147f](https://github.com/d1onys1us/raiko/commit/49d147f54fc187a0cffd1767af47fcc5783496a6))
* use stdin instead of sgx tmp file ([0d33aa8](https://github.com/d1onys1us/raiko/commit/0d33aa81fadeab27e45e6632defa0e0d8ce293d4))


### Bug Fixes

* different manifest in docker and local ([#117](https://github.com/d1onys1us/raiko/issues/117)) ([52999d6](https://github.com/d1onys1us/raiko/commit/52999d664a44ad86f4a69392f76353fc656821ff))
* enable the mpt cache ([#62](https://github.com/d1onys1us/raiko/issues/62)) ([46825d6](https://github.com/d1onys1us/raiko/commit/46825d66a2edfc8ce0e2acfb2e6e272645d79956))
* fetch history headers ([#100](https://github.com/d1onys1us/raiko/issues/100)) ([4fd70ee](https://github.com/d1onys1us/raiko/commit/4fd70eee7b5a64173549d3e466ab4bd7fbf2a33b))
* **lib:** temporarily disable kzg check in sgx/sp1 provers ([#157](https://github.com/d1onys1us/raiko/issues/157)) ([039d2fa](https://github.com/d1onys1us/raiko/commit/039d2fae62a7ec7d66c40d73cc1a47c65bf87c23))
* not optional alloy-sol-types ([8afb0d8](https://github.com/d1onys1us/raiko/commit/8afb0d89ded36dbeae74486841313633a94d7997))
* **raiko:** fix sticky invalid tx state ([#184](https://github.com/d1onys1us/raiko/issues/184)) ([99f5580](https://github.com/d1onys1us/raiko/commit/99f558088437af32e76e04d0529ea0715a163d40))


### Performance Improvements

* only filter once ([e1f5d41](https://github.com/d1onys1us/raiko/commit/e1f5d411a496a6d563ae8db61b164a0b77928884))
