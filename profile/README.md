# Verify all software.

Theorem does research and engineering in formal verification and AI.

## OSS Verify: free formal verification for open source

OSS Verify proves that an open-source project's fuzz targets can't crash on any input up to 64 MiB. The theorems are about the compiled RISC-V binary, not the source code, and the Rocq kernel checks every proof. Qualifying projects pay nothing.

**[Enroll your project](https://theorem.dev/oss-verify/#how-to-enroll)**

| Repository | What it holds |
|---|---|
| [oss-verify](https://github.com/theorem-labs/oss-verify) | Enrollment and build instructions. To enroll, open a pull request that adds your project. |
| [oss-verify-proofs](https://github.com/theorem-labs/oss-verify-proofs) | Theorem statements for 2,148 fuzz targets in 427 OSS-Fuzz projects, proofs for 60 of them, and the binaries they are about |
| [rocq-linux-process-semantics](https://github.com/theorem-labs/rocq-linux-process-semantics) | A Rocq model of a Linux process that runs a RISC-V binary. The statements are stated over it. |
| [static-asan](https://github.com/theorem-labs/static-asan) | The static AddressSanitizer for musl that the sanitizer builds use |

Questions: [oss-verify@theorem.dev](mailto:oss-verify@theorem.dev)
