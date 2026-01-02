# age-xwing

an implementation of the [MLKEM768-X25519 post-quantum recipient type](https://github.com/C2SP/C2SP/blob/main/age.md#the-mlkem768-x25519-ie-x-wing-hybrid-post-quantum-recipient-type). spun out from [chiffrage](https://github.com/thrzl/chiffrage).

intended for use with the [rage](https://github.com/str4d/rage) crate.

the only changes that will likely be made in the future will be using a more singular crypto library, like ring or aws-lc-rs.

---

the project relies on the `secrecy` and `zeroize` crates to safely manage data dealing with the `HybridIdentity` type.
