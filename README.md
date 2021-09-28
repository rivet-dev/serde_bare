# serde_bare

[![builds.sr.ht status](https://builds.sr.ht/~tdeo/serde_bare.svg)](https://builds.sr.ht/~tdeo/serde_bare?)

An implementation of the [BARE](https://baremessages.org) encoding format draft for Rust using [Serde](https://serde.rs).

BARE is a simple and easy to implement non-self-describing binary serialization format.  
It has similarities with [Bincode](https://github.com/bincode-org/bincode), but BARE is designed to be usable from programming languages other than Rust.

## Links

Mailing list: https://lists.sr.ht/~tdeo/serde_bare  
Ticket tracker: https://todo.sr.ht/~tdeo/serde_bare  

## Stability

Before version 1.0.0, minor version bumps (such as 0.1.0 to 0.2.0) may include changes to how data is serialized and deserialized.
This may be due to changes in the BARE specification draft, or changes in the mapping between Serde's data model and BARE's.

After version 1.0.0, updates within a major version (such as 1.0.0 to 1.1.0) will not change how data is serialized and deserialized.
Major version bumps (such as 1.0.0 to 2.0.0) may change the way data is serialized and deserialized.

There were no known changes to serialized and deserialized forms of types between versions 0.4.0 and 0.5.0.

## License

Licensed under either of Apache License, Version 2.0 or MIT license at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this crate by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
