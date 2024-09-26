# awesome-plonky3
A curated list of Plonky3 resources, libraries, tools and more.

Polygon [Plonky3](https://github.com/Plonky3/Plonky3), built by Polygon Zero team, is a toolkit for implementing polynomial IOPs (PIOPs), such as PLONK and STARKs, allowing developers to configure a variety of to-spec implementations from a single ZK proving system.

## Examples
- [Fibonacci Air](https://github.com/BrianSeong99/plonky3_fibonacci) - Learn the basics of Writing Air Constraints and Execution traces.
- [Range Check Air](https://github.com/BrianSeong99/plonky3_rangecheck) - Learn how to compare values in Air Contraints, and optimize on constraint degrees.
- [Keccak Air](https://github.com/Plonky3/Plonky3/tree/main/keccak-air) - Learn how to generate keccak hash proof in Air Constraints in multiple field(Babybear, Goldilocks, Koala, Mersenne31) and hash(Keccak, Poseidon2, Sha256) configurations
- [Poseidon2 Air](https://github.com/Plonky3/Plonky3/tree/main/poseidon2-air) - Learn how to generate poseidon2 hash proof in Air Constraints.

## Videos
- [The origin of Plonky3 by Daniel Lubarov](https://www.youtube.com/watch?v=giFA3UXbu_s) - Talk from the early stage of development of Plonky3.
- [Plonky3: Past, Present, Future by Daniel Lubarov](https://www.youtube.com/watch?v=203M0Q8iKso) - A general rundown of Plonky3 and its future.
- [Aggregation Day : Plonky3, Type 1, Miden](https://www.youtube.com/watch?v=j9KZixZqpAM) - A panel with Brenden, Danile, Bobbin from Polygon team, Uma from Succinct, and Eli from Starkware.

## Builds
- zkVMs
  - [SP1 from Succinct Labs](https://github.com/succinctlabs/sp1) - Performant Risc-V based zkVM that can prove Rust code execution.
  - [Valida from Lita Foundation](https://github.com/valida-xyz/valida) - Performant custom zk-friendly instruction sets that can prove Rust code execution.
  - [Powdr Toolkit from Powdr Labs](https://github.com/powdr-labs/powdr) - A toolkit for building zkVM or zkSystems, supports multiple proving backends including Plonky3.
- DSL
  - [Lurk from Argument Computer Corporation](https://github.com/argumentcomputer/lurk) - lurk is the newest and most performant implementation of Lurk, built on Plonky3 and Sphinx (our friendly fork of SP1).
- Hardware
  - [Fabric Plonky3 VPU](https://www.fabriccryptography.com/blog/polygon-plonky) - Verifiable Processing Unit (VPU) for Plonky3.

# Contributing
Contributions are very welcome!

Please have a look at [Contribution Guide](./contributing.md).

