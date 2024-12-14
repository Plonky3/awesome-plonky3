<div align="center">
  <h1 align="center">awesome Plonky3</h1>

A curated list of Plonky3 resources, libraries, tools and more.

  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="https://github.com/Plonky3/awesome-plonky3/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Plonky3/awesome-plonky3">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

</div>

# awesome-plonky3
A curated list of Plonky3 resources, libraries, tools and more.

Polygon [Plonky3](https://github.com/Plonky3/Plonky3) is a toolkit for implementing polynomial IOPs (PIOPs), such as PLONK and STARKs, allowing developers to configure a variety of to-spec implementations from a single ZK proving system.

> Contributions are very welcome! Please have a look at [Contribution Guide](./contributing.md).

## Projects
### zkVMs
- **[SP1 zkVM](https://github.com/succinctlabs/sp1) from Succinct Labs**: Performant Risc-V based zkVM that can prove Rust code execution.
- **[Valida zkVM](https://github.com/valida-xyz/valida) from Lita Foundation**: Performant custom zk-friendly instruction sets that can prove Rust code execution.
- **[Powdr zkVM](https://github.com/powdr-labs/powdr) Toolkit from Powdr Labs**: A toolkit for building zkVM or zkSystems, supports multiple proving backends including Plonky3.

### DSL
- **[Lurk](https://github.com/argumentcomputer/lurk) from Argument Computer Corporation**: Lurk is a Turing-complete programming language for zk-SNARKs, built on Plonky3 and Sphinx (our friendly fork of SP1).

### Hardware
- **[Plonky3 VPU](https://www.fabriccryptography.com/blog/polygon-plonky) from Fabric Crypto**: Verifiable Processing Unit (VPU) for Plonky3.

## Benchmarks

- **[Bench mark guide](https://github.com/Plonky3/Plonky3?tab=readme-ov-file#benchmarks)**: A guide to run your own benchmarks in Plonky3 using Poseidon2, Keccak, and Blake3 Air Constraints and various Plonky3 fields and hashes settings.
- **[Small Fields in Plonky3 & Comparison](https://hackmd.io/@Syxton/small_fields_in_plonky3)**: A comparison between small fields in Plonky3 and their performance.

## Papers

- **[Circle Stark](https://eprint.iacr.org/2024/278)**: Circle STARKs its a scheme that enables the STARK prover to work over the finite fields such as Mersenne 31 prime (M31).
- **[Reed-Solomon Codes over the Circle Group](https://eprint.iacr.org/2023/824)**: Discusses of Reed-Solomon codes over the circle group. Note that this got replaced by circle stark techniques in Plonky3.
- **[Poseidon2 in Plonky3](https://hackmd.io/@sin7y/r1VOOG8bR?utm_source=preview-mode&utm_medium=rec)**: Explores the implementation of Poseidon2 Hash in Plonky3 and a simple Bench test.

## Audits
- **[Plonky3 Audit](https://leastauthority.com/blog/audits/audit-of-plonky3/)**: Plonky3 Audit Report by Least Authority Team.

## Educational Resources

### Blogs

- **[Lita's Plonky3 Doc](https://lita.gitbook.io/lita-documentation/architecture/proving-system-plonky3)**: Lita Foundation's Plonky3 TLDR documentation.
- **[SP1 zkVM Source Code Walkthrough](https://trapdoortech.medium.com/zero-knowledge-proof-introduction-to-sp1-zkvm-source-code-d26f88f90ce4)**: Based on Plonky3, SP1 enhances the AIR description of chip interconnection and uses the LogUp algorithm to achieve a complete description of the RISC-V CPU-based virtual machine constraints.

### Examples/Tutorials:
- **[Keccak Air](https://github.com/Plonky3/Plonky3/tree/main/keccak-air)**: Learn how to write keccak hash Air Constraints and prove in various field and hash configs.
- **[Poseidon2 Air](https://github.com/Plonky3/Plonky3/tree/main/poseidon2-air)**: Learn how to write poseidon2 hash Air Constraints and prove in various field and hash configs.
- **[Blake3 Air](https://github.com/Plonky3/Plonky3/tree/main/blake3-air)**: Learn how to write blake3 hash Air Constraints and prove in various field and hash configs.
- **[Fibonacci Air](https://github.com/BrianSeong99/plonky3_fibonacci)[[video](https://youtu.be/2WjcXZYo7eA?si=289iwzLUJlhndVYa&t=1990)]**: Learn the basics of Writing Air Constraints and Execution traces.
- **[Range Check Air](https://github.com/BrianSeong99/plonky3_rangecheck)[[video](https://www.youtube.com/live/c8y7l3Ee70g?feature=shared&t=986)]**: Learn how to compare values in Air Contraints and how to optimize constraint degrees.

### Lectures/Presentations:
- **[Introduction to Plonky 1, 2, 3](https://www.youtube.com/live/v9xZrhAuTio)**: An introduction to Plonky by Daniel Lubarov.
- **[The origin of Plonky3](https://www.youtube.com/watch?v=giFA3UXbu_s)**: Early stage of development of Plonky3 by Daniel Lubarov.
- **[Plonky3: Past, Present, Future](https://www.youtube.com/watch?v=203M0Q8iKso)**: A generalized overview of Plonky3 and its future by Daniel Lubarov
- **[Aggregation Day : Plonky3, Type 1, Miden](https://www.youtube.com/watch?v=j9KZixZqpAM)**: A panel with Brendan, Daniel, and Bobbin from Polygon; Uma Roy, of Succinct Labs, and Eli Ben-Sasson, of Starkware.
- **[Build with Plonky2 and Plonky3](https://www.youtube.com/watch?v=HPu_fSvjAV0)**: A panel with Paul G from Polygon, Ratan from Succinct, and Garvit from Electron on building with Plonky2 and Plonky3.

## Miscs
- **[Plonky3 Discord Channel](https://discord.gg/dM64bMSRtM)**: Plonky3 Discord Channel for discussion and support.
- **[Plonky3 Grant - SoulForge](https://github.com/zk-bankai/soulforge)**: $100k dedicated to the Soul Society of Plonky3/Circom Development supported by Polygon.
