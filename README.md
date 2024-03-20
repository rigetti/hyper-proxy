# hyper-proxy

A fork of https://github.com/tafia/hyper-proxy with https://github.com/tafia/hyper-proxy/pull/38 merged.

- Updates dependencies such that the transitive dependency on [`ring`](https://crates.io/crates/ring) is `~0.17`, enabling PowerPC compilation (see [issue #1904](https://github.com/briansmith/ring/issues/1904))
- Keeps dependency of [`http`](https://crates.io/crates/http) to `~0.2` which [`tonic`](https://crates.io/crates/tonic) and others require ([`hyper-proxy2`](https://crates.io/crates/hyper-proxy2) requires `http ~1`)
