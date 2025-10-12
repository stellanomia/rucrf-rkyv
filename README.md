# rucrf-rkyv

This is a fork of [daac-tools/rucrf](https://github.com/daac-tools/rucrf) with `rkyv` support.

This fork exists to provide `rkyv` serialization for use in [vibrato-rkyv](https://github.com/stellanomia/vibrato-rkyv).

## Changes

-   Replaced `bincode` with `rkyv`.
-   Added `#[derive(Archive, Serialize, Deserialize)]` to necessary structs.

## License

Licensed under the same terms as the original library (MIT OR Apache-2.0).

---

For documentation on the original `rucrf` library, please see the [original repository](https://github.com/daac-tools/rucrf).
