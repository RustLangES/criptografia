# 🔐 **Applied Cryptography with Rust**  

🌟 A curated collection of tools, libraries, and resources in Rust for working with cryptography. Explore the power of Rust in the world of digital security and privacy! 🚀  

## 📖 **Why Rust for Cryptography?**  
Rust offers security, efficiency, and support for concurrent programming, making it an ideal language for building reliable and scalable cryptographic applications and tools. 💪  

With these resources, you can dive into the exciting world of cryptography and zero-knowledge proofs using Rust. 🚀  

---

## 🛠️ **Libraries and Projects**
* [Post-Quantum](#post-quantum)
  * [PQS Libraries](#pqs-libraries)
* [ZKPs](#zero-knowledge)
  * [AI-ZKML-ZKVM](#ai-zkml-zkvm)
  * [Educational Resources](#educational-resources)
  * [Advanced ZKP Libraries](#advanced-zkp-libraries)
  * [ZKTLS](#zktls)
  * [Tools and Projects](#tools-and-projects)
* [MPC](#secure-multiparty-computation)
  * [MPC Libraries](#mpc-libraries)
  * [MPC Frameworks](#mpc-frameworks)
  * [MPC Tools](#mpc-tools)
* [FHE](#fully-homomorphic-encryption)
  * [FHE Libraries](#fhe-libraries)
* [Hash Function](#hash-function)
  * [Hash Functions and Friends](#hash-functions-and-friends)
  * [Poseidon](#poseidon)
  * [Password-Hashing-Functions](#password-hashing-functions)

## Post-Quantum
### PQS Libraries
* **Liboqs-rust**  
  * 📚 **Description:**  
    Liboqs-rust is a Rust binding for the liboqs library, developed by the Open Quantum Safe project. It provides tools to experiment and integrate post-quantum cryptography algorithms, designed to resist quantum computing attacks.  

  * 🔧 **Key features:**  
      - Support for post-quantum digital signature algorithms and KEMs (Key Encapsulation Mechanisms).  
      - Compatible with the native C library, enabling seamless integration in Rust-based projects.  
      - Focused on experimental applications and research in post-quantum cryptography.  
      - Compatible with a wide range of approved and experimental algorithms.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/open-quantum-safe/liboqs-rust)  

* **Kyber**  
  * 📚 **Description:**  
    Kyber is a Rust implementation of the post-quantum cryptography algorithm Kyber, which is part of the NIST post-quantum cryptography standardization process finalists. This algorithm is designed to provide security resistant to quantum computing attacks in key generation and exchange.  

  * 🔧 **Key features:**  
      - Based on lattice-based cryptography scheme.  
      - Efficient in terms of performance and resource usage, suitable for practical applications.  
      - Designed to ensure confidentiality and security even against quantum computing attacks.  
      - Rust implementation to leverage its security and performance.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/Argyle-Software/kyber)  
      - [Documentation](https://pq-crystals.org/kyber/)  

* **Dilithium**  
  * 📚 **Description:**  
    Dilithium is a Rust implementation of the post-quantum digital signature algorithm CRYSTALS-Dilithium, one of the schemes selected for standardization by NIST. This scheme is based on lattices and designed to offer security against quantum computing attacks, maintaining a balance between performance, signature size, and keys.  

  * 🔧 **Key features:**  
      - Based on lattice-based cryptography.  
      - Security resistant to quantum computing, ideal for future applications.  
      - Optimal performance in signature generation and verification.  
      - Rust implementation to ensure code reliability and security.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/Argyle-Software/dilithium)  
      - [Documentation](https://pq-crystals.org/dilithium/)  

* **SPHINCS+**  
  * 📚 **Description:**  
    SPHINCS+ is a Rust implementation of the post-quantum digital signature scheme SPHINCS+, designed to resist quantum computing attacks. This scheme is based on hash trees and is completely free of algebraic structures, making it highly secure and flexible for various applications.  

  * 🔧 **Key features:**  
      - Based on hash-based cryptography, without algebraic structures.  
      - Security resistant to quantum computing, ideal for future scenarios.  
      - Offers multiple configurations that allow balancing performance, signature size, and keys.  
      - Rust implementation for high security and reliability.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/Argyle-Software/sphincsplus)  
      - [Documentation](https://sphincs.org/)  
      
* **zkDilithium**  
  * 📚 **Description:**  
    zkDilithium is a Rust implementation that combines the CRYSTALS-Dilithium digital signature scheme with zero-knowledge proofs (ZKPs). This innovative approach ensures signature authenticity while maintaining data privacy, making it ideal for applications where confidentiality and security are critical.  

  * 🔧 **Key features:**  
      - Based on CRYSTALS-Dilithium, a digital signature scheme resistant to quantum attacks.  
      - Integrates zero-knowledge proofs (ZKPs) to preserve privacy.  
      - Designed to provide authenticity and confidentiality simultaneously.  
      - Rust implementation to leverage its efficiency and security.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/guruvamsi-policharla/zkdilithium)
        
* **QuantCrypt**  
  * 📚 **Description:**  
    QuantCrypt is a Rust implementation of a series of post-quantum cryptography algorithms, designed to offer security solutions resistant to quantum computing attacks. The library includes a variety of modern cryptographic algorithms adapted to support future threats from quantum computers.  

  * 🔧 **Key features:**  
      - Supports various post-quantum cryptography algorithms.  
      - Designed to be modular and extensible, allowing integration of new algorithms.  
      - Focus on performance and efficiency for real applications.  
      - Rust implementation to leverage its security and efficiency.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/codespree/quantcrypt)
      
* **pqcrypto**  
  * 📚 **Description:**  
    pqcrypto is a Rust library that implements a variety of cryptographic algorithms resistant to quantum computing. This library includes solutions for digital signatures, key exchange, and encryption, all designed to protect data against future advances in quantum computing.  

  * 🔧 **Key features:**  
      - Supports various post-quantum cryptography algorithms, including ciphers and signatures.  
      - Provides robust and efficient solutions for scenarios requiring high security.  
      - Rust implementation, ensuring high reliability and efficiency.  
      - Compatible with post-quantum cryptography standards and projects.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/rustpq/pqcrypto)  
      
* **Citadel Protocol**  
  * 📚 **Description:**  
    Citadel Protocol is a security solution designed to protect communication between distributed systems using advanced cryptography. This protocol focuses on mutual authentication, end-to-end encryption, and protection against external threats, with special attention to resistance against quantum attacks.  

  * 🔧 **Key features:**  
      - Mutual authentication based on advanced cryptography.  
      - End-to-end encryption to ensure data privacy.  
      - Resistance to quantum threats, ensuring future security of communications.  
      - Modular implementation that allows adaptation to different environments and security requirements.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/Avarok-Cybersecurity/Citadel-Protocol)
      
* **KyberLib**  
  * 📚 **Description:**  
    KyberLib is a Rust implementation of the cryptography library based on the Kyber algorithm, one of the most promising post-quantum encryption algorithms. This library provides an efficient and secure implementation of the Kyber algorithm for applications requiring resistance against quantum computing attacks.  

  * 🔧 **Key features:**  
      - Efficient implementation of the Kyber encryption algorithm for optimal performance.  
      - Designed to be resistant to quantum computing attacks.  
      - Rust implementation ensuring efficiency and security.  
      - Support for various configurations and key sizes to adapt to different needs.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/sebastienrousseau/kyberlib)  

* **faest-rs**  
  * 📚 **Description:**  
    faest-rs is a Rust implementation of the FAEST signature scheme (Fast and Efficient Signature Scheme). This scheme provides efficient and secure digital signatures, adapted to resist quantum attacks, using modern cryptography techniques based on hard-to-solve mathematical problems.  

  * 🔧 **Key features:**  
      - Based on the FAEST scheme for fast and secure digital signatures.  
      - Designed to be resistant to quantum computing attacks.  
      - Rust implementation to leverage its efficiency and security.  
      - Allows efficient and scalable signature verification.  

  * 🌐 **Resources:**  
      - [GitHub Repository](https://github.com/ait-crypto/faest-rs)  

## Zero-Knowledge
📖 **What are Zero-Knowledge Proofs (ZKPs)?**

**Zero-knowledge proofs** are a type of cryptographic protocol that allows one party (the "prover") to demonstrate that they possess certain information without revealing the information itself. ZKPs are fundamental for applications that require high security and privacy, such as blockchain transaction verification without compromising data confidentiality.

### AI-ZKML-ZKVM
-------
* **EZKL**  
  * 📚 **Description:** EZKL enables AI model verification and analysis using zero-knowledge proofs (ZKPs) without exposing sensitive data. Supports ONNX format models and automates proof generation, facilitating ZKP integration in AI/ML applications.  
  * 🔧 **Key features:**  
      - Compatible with Python, JavaScript, Rust, and CLI.  
      - Automated proof generation without need for cryptography expertise.  
      - Uses **Lilith**, a cloud computing cluster, for large-scale proofs.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/zkonduit/ezkl)  
    - [Website](https://ezkl.xyz/)  
    - [Documentation](https://docs.ezkl.xyz/)

* **ProveKit (WorldCoin)**
  *  **📚 Description:** ProveKit is an open-source tool designed to facilitate the implementation and verification of advanced cryptographic proofs. Developed by World Foundation, this library aims to simplify the creation of secure systems that use techniques like zero-knowledge proofs (ZKP) or garbled circuits, allowing developers to protect sensitive data and validate computations without compromising privacy.
  *  **🔧 Key features:**
     * Support for generation and verification of zero-knowledge proofs.
     * Integration with multi-party computation (MPC) protocols for secure calculations.
     * High-level tools to build applications with guaranteed privacy.
     * Compatible with languages like Rust or Python, focused on performance and security.
     * Detailed documentation to facilitate adoption in real projects.
  *  **🌐 Resources:**
     * [GitHub Repository](https://github.com/worldfnd/ProveKit) 

* **Mopro**
  * **📚 Description:** Mopro is an open-source library designed to facilitate the integration of advanced cryptographic proofs in mobile applications. Developed by zkMoPro, this tool allows developers to implement zero-knowledge proofs (ZKP) efficiently, protecting sensitive data and enabling secure computations without compromising privacy, with special focus on mobile platforms like iOS and Android.
  * **🔧 Key features:**
    * Support for generation and verification of zero-knowledge proofs on mobile devices.
    * Optimized integration for mobile platforms, with Rust bindings and iOS/Android compatibility.
    * High-level tools to build applications with guaranteed privacy in mobile environments.
    * Focused on performance and security, leveraging the power of languages like Rust.
    * Detailed documentation and examples to facilitate adoption in real projects.
  * **🌐 Resources:**
    * [GitHub Repository](https://github.com/zkmopro/mopro)
    * [Documentation](https://zkmopro.org/docs/intro)

* **Powdr**
  * 📚 **Description:** Powdr is a tool designed to facilitate the construction of zero-knowledge virtual machines (zkVMs) and similar proof frameworks. Its main goal is to improve productivity, security, and performance in the development of these technologies. 

  * 🔧 **Key features:**

     *  Modular and extensible, ideal for building custom zkVMs.
     *   Support for backends like Plonky3, Halo2, and eSTARK.
     *   Compilation transparency, with readable and inspectable artifacts.
     *   Complete automation of proof and witness generation.

  * 🌐 **Resources:**  
     - [Documentation](https://docs.powdr.org/)  
     - [GitHub Repository](https://github.com/powdr-labs/powdr?utm_source=chatgpt.com) 

* **OpenVM**  
  * 📚 **Description:** A modular and extensible zkVM framework designed for customization and compatibility with advanced proofs. Allows executing unlimited-length programs, performing on-chain proofs, and supports extensions like ECDSA and modular arithmetic.  
  * 🔧 **Key features:**  
    *  Unlimited-length Rust program proofs.  
    *  On-chain verification.  
    * Advanced extensions for custom proofs.  
* 🌐 **Resources:**  
  - [Blog](https://blog.axiom.xyz/openvm)  
  - [GitHub Repository](https://github.com/openvm-org/openvm)  
  
 * **Delphinus zkWASM**  
  * 📚 **Description:** zkWASM is a zero-knowledge virtual machine designed to execute WASM (WebAssembly) with support for zero-knowledge proofs. Provides efficient and scalable infrastructure for applications requiring privacy and cryptographic verification.  
  * 🔧 **Key features:**  
    * Compatible with WASM to execute common applications in ZK environments.  
    * Advanced tools to generate zero-knowledge proofs in WASM.  
    * Optimized scalability for high-performance applications.  
  * 🌐 **Resources:**  
     - [Website](https://delphinuslab.com/zk-wasm/)  
     - [GitHub Repository](https://github.com/DelphinusLab/zkWasm)  

* **zkMove**  
  * 📚 **Description:** zkMove is a bytecode-based virtual machine designed to use the Move language, providing advanced capabilities for zero-knowledge proofs and secure execution in blockchain environments.  
  * 🔧 **Key features:**  
    * Support for zero-knowledge proofs in Move bytecode.  
    * High efficiency in executing Move-based smart contracts.  
    * Optimization for scalable and secure blockchain environments.  
  * 🌐 **Resources:**  
     - [Website](https://www.zkmove.net/)  
     - [GitHub Repository](https://github.com/young-rocks/zkmove)  

* **zkRiscV**  
  * 📚 **Description:** zkRiscV is a virtual machine based on the RISC-V RV32I instruction set. Designed to execute programs with zero-knowledge proofs, offers compatibility with one of the most used instruction sets in hardware.  
  * 🔧 **Key features:**  
    * Compatible with RISC-V RV32I instruction set.  
    * Ideal for creating and executing zero-knowledge programs.  
    * Efficient and customizable infrastructure for advanced developers.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/lucasgleba/zkRiscV)  

* **OlaVM**  
  * 📚 **Description:** OlaVM is a zero-knowledge virtual machine compatible with Ethereum. Allows developers to execute smart contracts with advanced privacy using ZK technology.  
  * 🔧 **Key features:**  
    * Fully compatible with Ethereum Virtual Machine (EVM).  
    * Provides privacy and cryptographic verification in smart contracts.  
    * Optimized approach for advanced decentralized applications.  
  * 🌐 **Resources:**  
     - [Website](https://olavm.org/)
     - [GitHub Repository](https://github.com/Sin7Y/olavm)

* **Risc0**  
  * 📚 **Description:** Risc0 is a general-purpose virtual machine based on RISC-V that integrates ZK technology for zero-knowledge proofs. Ideal for executing programs with advanced privacy in any context.  
  * 🔧 **Key features:**  
    * Support for RISC-V instruction set.  
    * Generalized zero-knowledge functionality for multiple applications.  
    * Modular design for flexibility in implementation and development.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/risc0/risc0)  

* **Miden VM**  
  * 📚 **Description:** Miden VM is a STARK-based virtual machine designed to provide zero-knowledge proofs with high scalability and performance. Backed by Polygon and ideal for modern blockchain applications.  
  * 🔧 **Key features:**  
    * Based on STARK technology for fast and secure proofs.  
    * Optimized scalability for large data volumes.  
    * Advanced architecture to support multiple blockchain use cases.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/0xPolygonMiden/miden-vm)  
   
* **Succinct SP1**  
  * 📚 **Description:** SP1 is a system developed by Succinct Labs that allows executing complete virtual machines within Ethereum smart contracts, using zero-knowledge proof technology to verify off-chain execution. Designed to optimize computation within the blockchain ecosystem, providing efficient solutions for complex applications.  
  * 🔧 **Key features:**  
    * Execution of complete virtual machines within Ethereum smart contracts.  
    * Use of zero-knowledge proofs to verify off-chain execution.  
    * Compatibility with multiple advanced blockchain applications.  
    * Optimized scalability for high computational demand environments.  
    * Reduction of computational costs through off-chain validation.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/succinctlabs/sp1)  
     - [Official Documentation](https://docs.succinct.xyz/docs/introduction)  

* **Delphinus zkWasm**  
  * 📚 **Description:** zkWasm is an infrastructure developed by Delphinus Lab that allows executing WebAssembly (WASM) programs with verification through zero-knowledge proofs. Combines WASM flexibility with zk-SNARKs cryptographic security, enabling efficient and secure off-chain validations within the blockchain ecosystem. Oriented to facilitate zkDApps development and improve scalability of complex decentralized applications.  
  * 🔧 **Key features:**  
    * Execution of WebAssembly (WASM) programs with cryptographic verification.  
    * Use of zero-knowledge proofs (zk-SNARKs) to validate off-chain calculations.  
    * Support for multiple languages through WASM compilation.  
    * Modular approach to integrate with different blockchains.  
    * Optimized infrastructure to build high-performance zkDApps.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/DelphinusLab/zkWasm)  
     - [Official Website](https://www.delphinuslab.com/)  
   

* **zkMIPS (ZKM)**  
  * 📚 **Description:** ZKM is a general verifiable computing infrastructure based on MIPS microarchitecture and the **Plonky2** zero-knowledge proof system. Its goal is to empower Ethereum as a global settlement layer, allowing complex programs in languages like Go and Rust to be executed and their execution verified efficiently through zk-SNARKs. ZKM facilitates both local proof generation and use of a dedicated proving network (demo), with EVM-compatible verification for blockchain integrations.  
  * 🔧 **Key features:**  
    * Verifiable computing infrastructure built on MIPS and Plonky2.  
    * Support for proof generation in programs written in Go and Rust.  
    * Local proving options or through a Proving Network.  
    * Project template to generate EVM-compatible proofs and on-chain verification contracts.  
    * Direct integration with blockchains like Ethereum (e.g., Sepolia).  
    * Active development project with detailed guides for testing and deployment.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/zkMIPS/zkm)  
     - [Official Website / Registration](https://www.zkm.io/apply)  
     - [Testing Guide and Documentation](https://docs.zkm.io/introduction/)  

* **Polygon ZisK**  
  * 📚 **Description:** ZisK is a zero-knowledge virtual machine (zkVM) developed by Polygon, designed to execute arbitrary programs verifiably and trustlessly. Based on advanced zk technology like Plonky3 and RISC-V architecture, ZisK allows developers to generate and verify cryptographic proofs efficiently and flexibly. Written primarily in Rust and focuses on ease of ZK proof integration in scalable and private applications. Currently in active development and should not be used in production environments yet.  
  * 🔧 **Key features:**  
    * High-performance zkVM focused on verifiable proofs of arbitrary programs.  
    * Primary support for Rust, with plans to add other languages.  
    * Based on RISC-V architecture and Plonky3 technology for succinct proofs.  
    * Developer-friendly environment to integrate ZK in decentralized applications.  
    * Dual licensing: Apache 2.0 or MIT.  
    * Active development project — not yet production-ready.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/0xPolygonHermez/zisk)  
     - [Official Documentation](https://0xpolygonhermez.github.io/zisk/)  
      
* **Valida**  
  * 📚 **Description:** Valida is a zkVM (zero-knowledge virtual machine) designed by [Lita.xyz](https://github.com/lita-xyz) to execute and prove programs written in Rust, C, and WASM with verifiable execution proofs. Provides a custom LLVM toolchain and supports in-browser proving via WebAssembly. Though in **alpha** stage, Valida stands out for its multi-language versatility, cross-platform compatibility (x86 and ARM64 via Docker), and support for accelerated hash proving (Keccak, SHA256, etc.).  
  * 🔧 **Key features:**  
    * Compilation and execution proving for programs in **Rust**, **C**, and **WebAssembly**.  
    * Verifiable proofs in browser through `valida-basic-api-wasm` API.  
    * LLVM-based toolchain with `cargo +valida`, `valida run`, `valida prove`, `valida verify`.  
    * Partial `libc` support, and compatibility with accelerated Keccak (via custom crate).  
    * Installation via **Docker** (recommended for ARM64 and non-x86 platforms), or binaries for x86_64 Linux.  
    * Current limitations: no multithreading support, no file system/network access, and proving still **not fully sound** (verifier may still accept incorrect proofs).  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/lita-xyz/valida-releases)  
     - [Rust and C Examples](https://github.com/lita-xyz/rust-examples)  
     - [Latest Version (v0.9.0-alpha)](https://github.com/lita-xyz/valida-releases/releases)  

* **Triton VM**  
  * 📚 **Description:** Triton VM is a Turing-complete virtual machine designed to work with STARK-based computational integrity proofs, using Algebraic Execution Tables (AET) and Arithmetic Intermediate Representations (AIR). Allows executing programs alongside efficient generation and verification of cryptographic proofs that guarantee execution correctness. Its most notable feature is the ability to perform fast recursive verifications of STARK proofs, facilitating the construction of scalable and composable trust systems.  
  * 🔧 **Key features:**  
    * Turing-complete ISA with STARK arithmetic through AET and AIR.  
    * Efficient recursive verification of STARK computational integrity proofs.  
    * Interfaces for use via CLI, TUI, or as library with examples.  
    * Rust implementation, with dependency on `twenty-first` cryptographic library.  
    * Documentation available as self-hostable mdBook.  
    * Development project, with stable ISA but not yet recommended for production.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/TritonVM/triton-vm)  
    - [Crate on crates.io](https://crates.io/crates/triton-vm)  

* **Pico**  
  * 📚 **Description:** Pico is an open-source zkVM that combines specialized circuits with modular architecture to create custom and efficient zero-knowledge proofs.  
  * 🔧 **Key features:**  
    * Supports multiple proof backends to optimize performance.  
    * Allows integrating specific circuits to accelerate calculations.  
    * Compatible with RISCV, RECURSION, and EVM phases using STARK in KoalaBear and BabyBear.  
  * ⚠️ **Status:** Not audited, not recommended for production (February 2025).  
  * 🤝 **Contributions:** Welcome, with guide available in repository.  
  * 🌐 **Resources:**  
    - [GitHub](https://github.com/brevis-network/pico)
   
  * **Nexus zkVM**  
  * 📚 **Description:** Nexus zkVM is a modular, extensible, and optimized zero-knowledge virtual machine (zkVM) for proof generation, written in Rust and focused on performance and security. Developed with StarkWare collaboration, it is fully open and publicly specified, without proprietary code or obfuscation.  
  * 🔧 **Key features:**  
    * Modular architecture with isolated and optimized components.  
    * Secure and efficient default configuration for most cases.  
    * Extensible to support new languages, precompiles, and proof methods without vendor lock-in.  
    * Transparency and security guaranteed through open specifications and rigorous analysis.  
  * ⚠️ **Status:** Experimental, not currently recommended for production.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/nexus-xyz/nexus-zkvm)  
    - [Official Documentation](https://docs.nexus.xyz)
   
   * **Miden VM**  
  * 📚 **Description:** Miden VM is a STARK-based virtual machine written in Rust that automatically generates zk-STARK proofs of program execution, allowing verification of their correctness without needing to re-execute them or know the source code.  
  * 🔧 **Key features:**  
    * Turing-complete virtual machine with support for control flow, loops, and subroutines.  
    * Execution in multiple isolated contexts with dedicated memory.  
    * Native operations with 32-bit integers and integrated cryptographic functions (Rescue Prime Optimized).  
    * Support for nondeterminism and customizable hosts to connect with external data sources.  
    * Optimized standard library and support for external libraries.  
    * Parallelizable STARK proof generation to accelerate execution proving.  
  * ⚠️ **Status:** Alpha stage, not audited or production-ready.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/0xMiden/miden-vm)  
    - [Official Documentation](https://0xmiden.github.io/miden-vm/)  

* **Jolt**  
  * 📚 **Description:** Jolt is a zkVM for RISC-V designed to be the simplest, fastest, and most extensible of its kind. Implements the 32-bit Base Integer instruction set (RV32I). The project is in alpha stage and not suitable for production.  
  * 🔧 **Key features:**  
    * RISC-V based zkVM, with design focused on simplicity and performance.  
    * Modular implementation with CUDA acceleration support via `icicle` feature.  
    * Performance profiling with tools like tracing_chrome and supports continuous benchmarking.  
    * Open community for contributions, with complete documentation and quick start guide.  
  * ⚠️ **Status:** Alpha, no audit and not recommended for production.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/a16z/jolt)  
    - [Official Documentation (The Jolt Book)](https://jolt.a16zcrypto.com/)
   
  * **eigen-zkvm**  
  * 📚 **Description:** eigen-zkvm is a zkVM based on a layered proof system that allows writing zero-knowledge applications with proofs that require no trusted setup, maintain constant on-chain proof size, and reduce gas costs. Additionally generates Solidity verifiers.  
  * 🔧 **Key features:**  
    * Support for multiple proof systems: STARK, PLONK, and Groth16 through universal CLI `zkit`.  
    * Circom 2.x support.  
    * Proof composition: aggregation and recursion over STARK proofs.  
    * Snark proof recursion over STARK.  
    * Automatic Solidity verifier generation.  
    * GPU acceleration for proof generation (not open source).  
    * Based on RISC-V ISA.  
  * ⚠️ **Status:** Active but experimental.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/0xEigenLabs/eigen-zkvm)  

* **Ceno**  
  * 📚 **Description:** Ceno is an accelerated zero-knowledge virtual machine (zkVM) for RISC-V, based on a non-uniform and segmented proof system, using the GKR protocol. Developed in Rust and oriented to parallelization and optimization of the proving process.  
  * 🔧 **Key features:**  
    * RISC-V based zk virtual machine with support for parallel and segmented execution.  
    * GKR protocol for non-uniform proof generation.  
    * Practical examples for end-to-end proofs, including classic calculations like Fibonacci.  
    * Built in Rust with modern tools (cargo-make, rustup) for development and testing.  
    * Project under construction, not recommended for production.  
  * ⚠️ **Status:** Under construction, not suitable for production.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/scroll-tech/ceno)  

* **PetraVM**  
  * 📚 **Description:** PetraVM is a general-purpose virtual machine designed for succinct verification using the Binius proof system. Its execution model and ISA are optimized for efficient Binius proofs, supporting recursive verification, general computation via WebAssembly, and high-performance verifiable computing with its own language called PetraML.  
  * 🔧 **Key features:**  
    * Binary and arithmetic operations in binary field.  
    * Write-once memory model (VROM).  
    * Efficient recursion support.  
    * Modular instruction set with optional extensions.  
    * Support for function calls, control flow, and logical/comparison operations.  
    * Included examples: Fibonacci calculation and Collatz conjecture.  
    * Active development with growing instruction support.  
  * ⚠️ **Status:** Active development. Not all instructions fully supported yet.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/PetraProver/PetraVM)  
    - [Full Specification](https://petraprover.github.io/PetraVM/specification.html)  

* **zkSync Airbender**  
  * 📚 **Description:** zkSync Airbender is a set of build and proof tools for RISC-V programs within the zkSync ecosystem. It includes ZK circuit implementations for RISC-V, a RISC-V simulator, and utilities for witness generation, zero-knowledge proof creation, and verification.  
  * 🔧 **Key features:**  
    * Compilation and execution of programs on a simulated RISC-V architecture.  
    * Custom circuits for zero-knowledge proofs.  
    * CLI tools for end-to-end workflows (from source code to verification).  
    * Practical examples and detailed documentation for developers.  
    * Clearly defined security and contribution policy.  
    * Dual license: Apache 2.0 and MIT.  
  * ⚠️ **Status:** Active and maintained. Contributions encouraged per repository policy.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/matter-labs/zksync-airbender)  

### Educational-Resource
------
* **MyZKP**  
  * 📚 **Description:** An educational Rust implementation of zero-knowledge protocols built from scratch. Ideal for learning and experimenting with ZK proofs from the basics.  
  * 🔧 **Key features:**  
     * Educational design to understand core ZKP principles.  
     * Step-by-step construction in Rust.  
  * 🌐 **Resources:**  
      * [GitHub Repository](https://koukyosyumei.github.io/MyZKP/index.html)  

### Advanced ZKP Libraries
----------

* **Halo2**  
  * 📚 **Description:** Halo2 is a zero-knowledge proof library providing an efficient architecture for zkSNARKs in Rust. It is particularly known for its focus on efficiency and scalability.  
  * 🔧 **Key features:**  
    * zkSNARK optimization using arithmetic on elliptic curves.  
    * High-performance zero-knowledge proofs with low computational cost.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/zcash/halo2)  
    - [Documentation](https://zcash.github.io/halo2/)  

* **Plonky3**  
  * 📚 **Description:** Plonky3 is a toolkit for implementing polynomial IOPs (PIOPs), such as PLONK and STARKs. It supports multiple polynomial commitment schemes like Brakedown.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/Plonky3/Plonky3)  
    - [Awesome Plonky3](https://github.com/Plonky3/awesome-plonky3)  

* **Lambworks**  
  * 📚 **Description:** A library implementing SNARK and STARK provers, allowing SNARK customization. Provides cryptographic primitives, high performance, and user-friendly tools for working with ZK proofs. Supports multiple proof backends and frontends, targeting an efficient, production-ready library.  
  * 🔧 **Key features:**  
    * Implementation of SNARKs and STARKs.  
    * Support for cryptographic primitives.  
    * Performance optimization.  
    * Compatible with multiple proof backends.  
  * 🌐 **Resources:**  
    - [GitHub Repository](https://github.com/lambdaclass/lambdaworks)  
    - [Documentation](https://lambdaclass.github.io/lambdaworks/)  

* **Arkworks**  
  * 📚 **Description:** A Rust library suite providing tools for building ZK cryptography (ZKPs) and SNARKs. Enables efficient and secure proof creation for blockchain applications, supporting schemes like PLONK, Marlin, etc. Offers advanced functionality for polynomials, elliptic curves, and modular arithmetic.  
  * 🔧 **Key features:**  
    * Efficient implementations of finite fields and elliptic curves.  
    * SNARK systems like Groth16 and Marlin.  
    * Tools for R1CS circuit creation and polynomial algebra.  
    * Supports universal proofs and pairwise inner products.  
    * Resources for R1CS programming and SNARK proofs.  
   * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/arkworks-rs)  
     - [Documentation](https://arkworks.rs/)  

* **Binius**  
  * 📚 **Description:** Optimized Rust library for efficient multilinear polynomial commitments. Designed to improve performance of ZKVMs and advanced cryptographic proofs, especially on small-bit architectures.  
  * 🔧 **Key features:**  
    * Significant computational cost reduction in polynomial commitment schemes.  
    * Compatible with high-efficiency ZKVM proofs.  
    * Optimized for binary field towers in low-level architectures.  
    * Built in Rust for security and speed in critical operations.  
    * Apache 2.0 license, suitable for open-source and commercial projects.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/IrreducibleOSS/binius64)  
     - [Technical Publication on Binius](https://www.binius.xyz/basics)  

* **Bellman**  
  * 📚 **Description:** Bellman is a Rust library providing an efficient zk-SNARK implementation for zero-knowledge cryptography. Designed for building applications requiring blockchain validity proofs, including schemes like Groth16 and optimizations. Known for efficiency and scalability with a simplified interface.  
  * 🔧 **Key features:**  
    * Efficient zk-SNARK implementation, especially Groth16.  
    * Optimized for fast, low-computation proofs.  
    * Supports advanced algebraic structures like elliptic curves.  
    * Compatible with blockchain validity-proof applications.  
    * Focused on scalable and efficient execution.  
  * 🌐 **Resources:**  
     - [GitHub Repository](https://github.com/zkcrypto/bellman)  
     - [Official Documentation](https://docs.rs/bellman/)  

* **Spartan**

  * 📚 **Description:** Spartan is a Microsoft platform for creating and verifying zero-knowledge proofs (ZKPs). It is designed to be flexible and efficient, allowing developers to implement ZKPs in various applications, especially in blockchain environments. Spartan provides a set of tools that enables resource optimization in cryptographic proof execution, facilitating integration into decentralized systems.
  * 🔧 **Key Features:**

    * Flexible platform for creating ZKPs.
    * Computational resource optimization in proof execution.
    * Compatible with blockchain applications and decentralized systems.
    * Tools for large-scale creation and verification of cryptographic proofs.
  * 🌐 **Resources:**

    * [Spartan GitHub Repository](https://github.com/microsoft/Spartan)

* **Spartan2**

  * 📚 **Description:** Spartan2 is a Microsoft-developed tool providing a platform for efficient zero-knowledge proof (ZKP) execution. It is designed for integration into blockchain systems and enables building decentralized applications through cryptographic proofs. Spartan2 improves proof efficiency and optimizes resource usage for applications requiring large-scale validity proofs.
  * 🔧 **Key Features:**

    * ZKP implementation focused on proof efficiency.
    * Optimization to minimize computational resource usage and enhance scalability.
    * Tools for performing validity proofs in blockchain applications.
    * Easy integration with decentralized applications and blockchain platforms.
  * 🌐 **Resources:**

    * [Spartan2 GitHub Repository](https://github.com/microsoft/Spartan2)

* **Bulletproofs**

  * 📚 **Description:** Bulletproofs is an efficient zero-knowledge proof (ZKP) scheme that does not rely on a trusted setup. It provides compact and efficient range proofs, optimizing cryptographic proofs without needing trusted configurations. Bulletproofs is widely used in blockchain and cryptocurrency applications to ensure privacy and integrity without compromising performance.
  * 🔧 **Key Features:**

    * Compact range proofs without trusted setup.
    * Optimization of cryptographic efficiency.
    * Accelerated proofs for blockchain applications.
    * Ideal for environments with high privacy and scalability requirements.
  * 🌐 **Resources:**

    * [Bulletproofs GitHub Repository](https://github.com/dalek-cryptography/bulletproofs)
    * [Official Documentation](https://dalekcryptography.github.io/bulletproofs/)

* **Plonk**

  * 📚 **Description:** Plonk is an efficient and universal zero-knowledge proof system that allows verifying any computation within a cryptographic scheme without compromising security or trust. Plonk uses arithmetic over finite fields and is widely employed in blockchain to provide fast and scalable proofs without sacrificing privacy.
  * 🔧 **Key Features:**

    * Efficient proof system based on finite field arithmetic.
    * Universal proofs without requiring trusted setups.
    * Supports a wide range of applications and use cases in blockchain.
    * High scalability and speed compared to other ZKP schemes.
  * 🌐 **Resources:**

    * [Plonk GitHub Repository](https://github.com/dusk-network/plonk)
    * [Official Documentation](https://dusk-network.github.io/plonk/)

* **Jellyfish**

  * 📚 **Description:**
    Jellyfish is a Rust library developed by Espresso Systems that implements the PLONK zero-knowledge proof system and its extensions.

  * 🔧 **Key Features:**

    * Complete implementation of PLONK and its extensions.
    * Modularity and flexibility for different use cases.
    * Optimization for fast proof generation and verification.
    * Compatible with environments requiring privacy and scalability.

  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/EspressoSystems/jellyfish)

* **Nova**

  * 📚 **Description:**
    Nova is a high-speed recursive SNARK, a cryptographic system that allows a prover to demonstrate a mathematical statement to a verifier with a short proof and succinct verification. Nova supports Incrementally Verifiable Computation (IVC), meaning a prover can update a proof to include additional computation steps without recalculating the entire verification.
    This approach has applications in Rollups, Verifiable Delay Functions (VDFs), succinct blockchains, and verifiable state machines.

  * 🔧 **Key Features:**

    * Fastest prover among known recursive systems.
    * Constant verification circuit with roughly 10,000 multiplication gates.
    * Implemented with a cryptographic folding scheme reducing two NP statements to one.
    * Applications in Rollups, VDFs, and virtual machine execution like EVM and RISC-V.

  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/microsoft/Nova)

* **Kimchi**

  * 📚 **Description:** Kimchi is a zero-knowledge proof (ZKP) system designed to ensure programs execute correctly. It is part of the Mina project and allows creating compact, fast proofs to verify complex computations without revealing information.
  * 🔧 **Key Features:**

    * Fast proofs and efficient verifications.
    * Based on advanced cryptographic technology (Pasta elliptic curves).
    * Modular, with components for hashing, polynomial commitments, and more.
  * ⚠️ **Warning:** The project is under development, does not guarantee stability, and requires audits for production use.
  * 🤝 **Contributions:** Open to interested developers.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/o1-labs/proof-systems)

* **Lattirust**

  * 📚 **Description:** Lattirust is a collection of Rust libraries for building and experimenting with zero-knowledge proofs and lattice-based succinct arguments. It focuses on post-quantum cryptography and aims to be a modular, extensible platform for research and development.
  * 🔧 **Key Features:**

    * Implementation of algebraic structures compatible with arkworks.
    * Tools for estimating security of lattice problems.
    * Proof schemes like LaBRADOR and Lova based on lattices.
    * Modular architecture with multiple reusable crates.
  * ⚠️ **Warning:** Active development project. Subject to frequent changes and not recommended for production without audits.
  * 🤝 **Contributions:** Open to contributions. Maintained by Christian Knabenhans (EPFL).
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/lattirust)

* **ZK-Garage**

  * 📚 **Description:** ZK-Garage is a Rust implementation of the Plonk zero-knowledge proof (ZKP) system using the arkworks backend. It enables building efficient and flexible proofs, leveraging custom gates and lookups to improve performance and reduce the number of constraints.
  * 🔧 **Key Features:**

    * Compatible with multiple cryptographic curves via arkworks integration.
    * Support for custom gates and lookups, optimizing proof generation.
    * `plonk-hashing` module with optimized Poseidon hash implementation and planned support for Reinforced Concrete and Blake2s.
    * Detailed documentation in `plonk-book` explaining system internals and PLONK-specific features.
    * Build options allowing parallelization (`parallel`), inline assembly (`asm`), and circuit debugging tools (`trace`, `trace-print`).
  * ⚠️ **Warning:** Active development. Functional but may change; use caution in production.
  * 🤝 **Contributions:** Open to developers via GitHub and Discord for discussion and support.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/ZK-Garage/plonk)

### ZKTLS

* **TLSNotary**

  * 📚 **Description:** TLSNotary is an open-source protocol and tool that enables cryptographic auditing of TLS sessions, providing verifiable proof of communications between a client and a server without compromising client privacy.

  * 🔧 **Key Features:**

    * Generation of cryptographic proofs for TLS sessions.
    * Client privacy guaranteed during auditing.
    * Compatible with a wide range of applications and web services.
    * Ideal for use cases requiring transparency and verifiability, such as financial or legal audits.
    * Implemented in Python, designed for accessibility and ease of use.

  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/tlsnotary/tlsn)
    * [Official Documentation](https://docs.tlsnotary.org/)

### Tools-and-Projects

* **zkemail**

  * 📚 **Description:** zkemail is a project focused on ensuring secure and private email communication using zero-knowledge proofs (ZKPs).
  * 🔧 **Key Features:**

    * Secure email communication through advanced cryptographic methods.
    * Uses zero-knowledge proofs to maintain user privacy.
  * 🌐 **Resources:**

    * [Official Site](https://prove.email)
    * [GitHub Repository](https://github.com/zkemail)
    * [Twitter](https://twitter.com/zkemail)

* **mopro**

  * 📚 **Description:** Mopro is an optimized library for zero-knowledge (ZK) proofs on mobile devices. It integrates with Circom and Halo2, significantly improving performance compared to traditional solutions like `snarkjs`. Its goal is to simplify ZK application development on mobile platforms.
  * 🔧 **Key Features:**

    * Integration with Circom and Halo2.
    * Optimized performance for mobile devices.
    * Simplified ZK application development.
  * 🌐 **Resources:**

    * [mopro GitHub Repository](https://github.com/zkmopro/mopro)
   
---

## Secure-Multiparty-Computation

---

### MPC-Libraries

* **Swanky**

  * 📚 **Description:** Swanky is a library designed to facilitate the development of Multi-Party Computation (MPC, Cómputo Multi-Partido) protocols. It provides tools to implement secure data exchange schemes and computational operations among multiple parties while maintaining data privacy.
  * 🔧 **Main features:**

    * Modular and flexible implementation for experimenting with MPC protocols.
    * Support for schemes like Garbled Circuits (GC) and Oblivious Transfer (OT).
    * Focused on providing a solid foundation for developers interested in research and production of MPC-based solutions.
  * 🌐 **Resources:**

    * [Swanky GitHub Repository](https://github.com/GaloisInc/swanky)

* **Smol-MPC**

  * 📚 **Description:** Smol-MPC is a lightweight and efficient library for implementing Multi-Party Computation (MPC, Cómputo Multi-Partido) protocols. Designed by HashCloak, this library focuses on providing a simple, flexible, and optimized solution for securely and privately performing collaborative computations among multiple participants.
  * 🔧 **Main features:**

    * Compatible with basic MPC protocols, allowing collaborative operations without compromising data privacy.
    * Lightweight and easy to integrate into projects, ideal for those seeking an accessible MPC library for experimentation or smaller applications.
    * Focused on minimalism, making it an excellent choice for developers starting with MPC without unnecessary complexity.
  * 🌐 **Resources:**

    * [smol-mpc GitHub Repository](https://github.com/hashcloak/smol-mpc)
    * [Documentation](https://docs.rs/smol-mpc/)

* **MPZ**

  * 📚 **Description:** MPZ is a collection of multi-party computation (MPC, computación multipartita) libraries written in Rust 🦀. The project aims to provide secure, efficient, modular, and portable MPC software, with a focus on usability.

  * ⚠️ **Notice:** This project is under active development and should not be used in production. There may be bugs and significant changes frequently. Use at your own risk.

  * 🔧 **Main features:**

    * Implementation of basic primitives for secure computation in decentralized environments.
    * DSL for creating boolean circuits declaratively, designed for multi-party computation.
    * Implementation of fundamental OT protocols to ensure privacy in secure computation operations.
    * Support for efficient conversions between different types of shares for secure operations.

  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/privacy-scaling-explorations/mpz)

### MPC-Frameworks

* **stoffelMPC**

  * 📚 **Description:** StoffelMPC is a framework for multi-party computation (MPC, Cómputo Multi-Partido). It allows developers to write MPC software in a domain-specific language that abstracts the internal details of MPC protocols.

These MPC programs are compiled to bytecode for the StoffelVM, a virtual machine that allows execution in a multi-party environment. Our implementation focuses on robust MPC protocols, as these are relevant in the context of MPC as a sidechain. This means MPC is used to provide the privacy layer currently missing in public blockchains.

* 🔧 **Main features:**

  * Allows writing programs in a domain-specific language, simplifying multi-party computation development.
  * Programs are compiled to bytecode to run on StoffelVM, a specialized virtual machine.
  * Focused on robust protocols, ideal for applications requiring high security and reliability.
  * Provides a privacy layer for public blockchains, protecting data and transactions.
* 🌐 **Resources:**

  * [GitHub Repository](https://github.com/hashcloak/stoffelMPC)

---

### MPC\_Tools

* **Garble-lang**

  * 📚 **Description:** Garble-lang is a simple programming language specialized in secure computation and executing calculations on encrypted data using garbled circuits. Its goal is to enable developers to implement private applications via multi-party computation (MPC, computación multipartita), protecting data privacy without decrypting it.
  * 🔧 **Main features:**

    * High-level language for building and executing garbled computation circuits.
    * Allows secure calculations on encrypted data without revealing sensitive information.
    * Facilitates the creation of privacy-requiring applications, such as smart contracts and private data analysis.
    * Provides tools for integration with other secure computation and privacy protocols.
    * Offers an efficient framework for implementing MPC.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/sine-fdn/garble-lang)
    * [Documentation](https://garble-lang.org)

* Tandem

  * 📚 **Description:** Tandem is an open-source, secure, and maliciously robust multi-party computation (MPC, computación multipartita) engine designed to be integrable and accessible. Its goal is to allow companies and developers to perform collaborative computations on encrypted data using garbled circuits, protecting privacy without revealing underlying information. Developed by the SINE Foundation, Tandem transforms sensitive data into value opportunities through advanced cryptography.

    * 🔧 **Main features:**

      * High-performance engine for running garbled circuits in secure two-party computation.
      * Allows computations on encrypted data without compromising party privacy.
      * Facilitates practical applications requiring confidentiality, such as joint data analysis and secure collaboration between organizations.
      * Includes tools like an HTTP server, a CLI client, and WebAssembly support, as well as integration with Garble, a high-level language for MPC.
      * Provides an efficient and user-friendly framework for implementing multi-party computation in real-world scenarios.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/sine-fdn/tandem)
    * [SINE Foundation Website](https://sine.foundation/tandem)

## Fully-Homomorphic-Encryption

---

### FHE-Libraries

* **tfhe-rs**

  * 📚 **Description:** Tfhe-rs is a Rust library implementing fully homomorphic encryption (TFHE). It provides an efficient and secure way to perform operations on encrypted data, allowing sensitive information to be processed without decryption.
  * 🔧 **Main features:**

    * Fully homomorphic encryption (TFHE) implementation.
    * Enables arithmetic and logical operations on encrypted data.
    * High efficiency in processing encrypted data.
    * Compatible with privacy and secure computation applications.
    * Facilitates the development of data protection and privacy solutions in decentralized environments.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/zama-ai/tfhe-rs)
    * [Documentation](https://docs.zama.ai/tfhe-rs)

* **Openfhe-rs**

  * 📚 **Description:** Rust implementation of OpenFHE, an open-source fully homomorphic encryption (FHE) framework. Allows operations on encrypted data without decryption, maintaining privacy during processing. OpenFHE is an emerging technology essential for privacy and secure computation applications in trusted environments.
  * 🔧 **Main features:**

    * Homomorphic encryption implementation in Rust.
    * Supports a wide variety of operations on encrypted data without decryption.
    * Based on OpenFHE, known for security and flexibility.
    * Enables developers to create applications that protect data privacy during processing.
    * Compatible with multiple advanced homomorphic encryption methods.
    * Optimized for secure computation and data protection applications.
    * Modular and extensible design for easy integration into different projects.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/fairmath/openfhe-rs)
    * [Documentation](https://openfhe-rust-wrapper.readthedocs.io/en/latest/)

* **Phantom-Zone**

  * 📚 **Description:** Phantom-Zone is a library enabling efficient and secure Multi-Party Computation (MPC, Cómputo Multi-Partido) protocol construction. Developed by Gauss Labs, it is designed to be scalable and applicable in high-privacy environments. Focuses on robust implementations for collaborative calculations without compromising data security.
  * 🔧 **Main features:**

    * Uses fully multiplicative homomorphic encryption for calculations on private inputs from multiple parties.
    * Offers two types of multi-party protocols: non-interactive and interactive.
    * Supports arithmetic operations and comparisons on 8-bit unsigned integers (FheUint8), handling overflow and divide-by-zero errors.
    * The library is experimental and should not be used in production for sensitive data due to lack of security auditing.

* 🌐 **Resources:**

  * [GitHub Repository](https://github.com/gausslabs/phantom-zone)

## Hash-Function

### Hash-Functions-and-Friends

* **RustCrypto/hashes**

  * 📚 **Description:** RustCrypto/hashes is a collection of cryptographic hash function implementations developed in Rust. The repository includes support for widely used hash algorithms designed to be secure and efficient. Essential for projects requiring data integrity, digital signature verification, and cryptographic applications.
  * 🔧 **Main features:**

    * Secure, actively developed implementations of hash functions like SHA-2, SHA-3, Blake2, and more.
    * Compatibility with authenticated hash algorithms like Poly1305.
    * Modular design for easy integration in Rust projects.
    * Focus on performance and security through optimized code and extensive testing.
    * Fully compatible with `no_std`, suitable for resource-constrained environments.
    * Actively maintained by RustCrypto community, with regular contributions and updates for Rust language support.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/gausslabs/phantom-zone)

* **BLAKE3**

  * 📚 **Description:** BLAKE3 is a modern cryptographic hash function designed to be fast, secure, and highly parallelizable. Developed by the BLAKE3 team, it combines features from algorithms like BLAKE2, SHA-3, and Merkle-Damgård, offering exceptional performance across platforms, from mobile devices to high-performance servers.
  * 🔧 **Main features:**

    * Faster than SHA-2 and SHA-3 hash functions in most environments.
    * Highly parallelizable, scaling on multi-core and SIMD hardware.
    * Supports incremental hashing, keyed hashing, and key derivation.
    * Built on a secure design using a Merkle tree, enabling efficient hashing of large datasets.
    * Implementations available in multiple languages, including Rust, C, Python, and more.
    * Audited and supported by a wide developer community.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/BLAKE3-team/BLAKE3)

* **RustCrypto/KDFs**

  * 📚 **Description:** RustCrypto/KDFs is a collection of Key Derivation Function (KDF) implementations developed in Rust. Supports widely used algorithms for generating secure keys from inputs like passwords or master keys. Designed for security, efficiency, and easy Rust project integration.
  * 🔧 **Main features:**

    * Supports KDF algorithms like HKDF (HMAC-based Extract-and-Expand Key Derivation Function) and PBKDF2 (Password-Based Key Derivation Function 2).
    * Secure and efficient design with performance optimization.
    * Compatible with `no_std`, suitable for constrained environments.
    * Modular, easy to integrate into Rust applications needing derived keys.
    * Maintained by RustCrypto community with regular contributions and thorough testing.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/RustCrypto/KDFs)

* **RustCrypto/universal-hashes**

  * 📚 **Description:** RustCrypto/universal-hashes is a collection of universal hash function implementations developed in Rust. Mainly used as building blocks for cryptographic algorithms, such as message authentication codes (MACs) and authenticated encryption (AEAD).
  * 🔧 **Main features:**

    * Implements universal hash functions like Poly1305 and GHASH (used in Galois/Counter Mode, GCM).
    * Secure, efficient, and easy to integrate into Rust applications.
    * Compatible with `no_std`, ideal for resource-constrained systems.
    * Modular and compatible with other RustCrypto components for smooth integration.
    * Actively maintained by RustCrypto community, focused on security and performance.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/RustCrypto/universal-hashes)

* **tiny-keccak**

  * 📚 **Description:** **tiny-keccak** is a minimalist, efficient Rust implementation of the Keccak hash function, also the basis of the SHA-3 standard. Lightweight and easy to use, ideal for applications needing a secure, high-performance hash in resource-limited environments.
  * 🔧 **Main features:**

    * Supports Keccak and SHA-3, including SHAKE (Extendable-Output Functions, XOFs) variants.
    * Lightweight, optimized for low resource consumption.
    * `no_std` compatible, suitable for embedded systems.
    * Easy integration into Rust projects due to modular design and clear documentation.
    * Maintained by the Rust community, emphasizing simplicity and security.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/debris/tiny-keccak)

### Poseidon

* **Poseidon252**

  * 📚 **Description:** **Poseidon252** is a highly efficient implementation of the Poseidon hash function, developed by the Dusk Network team in Rust. Poseidon is optimized for zk-SNARKs and zk-STARKs circuits, mainly used in advanced cryptography applications like privacy and zero-knowledge proofs.
  * 🔧 **Main features:**

    * Poseidon implementation over the 252-bit scalar field, ideal for elliptic curve cryptography and zero-knowledge proof applications.
    * Designed for efficiency in ZKP circuits, reducing constraints in proofs.
    * `no_std` compatible, suitable for embedded systems and resource-constrained environments.
    * Easy integration into cryptographic projects requiring secure, efficient hashing.
    * Actively maintained by Dusk Network team, focusing on privacy and scalability applications.

* 🌐 **Resources:**

  * [GitHub Repository](https://github.com/dusk-network/poseidon252)

* **Poseidon2**

  * 📚 **Description:** **Poseidon2** is an optimized implementation of the Poseidon hash function developed by **Horizen Labs** in Rust. Poseidon is a cryptographic hash algorithm specifically designed for zero-knowledge proof applications (zk-SNARKs and zk-STARKs), offering efficient construction in terms of circuit constraints.
  * 🔧 **Main features:**

    * Optimized Poseidon hash algorithm implementation for zk circuits.
    * Focused on improving performance and reducing constraints in zero-knowledge proofs.
    * `no_std` compatible, allowing integration into resource-constrained devices.
    * Ideal for privacy and security applications like smart contracts, digital identities, and decentralized systems.
    * Actively maintained by Horizen Labs, focusing on advanced cryptography applications.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/HorizenLabs/poseidon2)

* **Poseidon**

  * 📚 **Description:** **Poseidon** is a Rust implementation of the Poseidon hash function, designed by **Privacy & Scaling Explorations**. Optimized for zero-knowledge proofs (zk-SNARKs and zk-STARKs) and applications requiring efficiency and cryptographic security in advanced environments.
  * 🔧 **Main features:**

    * Poseidon implementation with support for highly customizable configurations depending on the field and zk circuit.
    * Specific optimizations to reduce constraints in zk circuits, improving proof performance.
    * Designed for easy integration with advanced cryptography and scalability projects.
    * `no_std` compatible, suitable for embedded or resource-constrained environments.
    * Actively maintained by Privacy & Scaling Explorations, focusing on scalability and privacy technologies.
  * 🌐 **Resources:**

  - [GitHub Repository](https://github.com/privacy-scaling-explorations/poseidon)

### Password-Hashing-Functions

* **RustCrypto/password-hashes**

  * 📚 **Description:** **RustCrypto/password-hashes** is a collection of Password Hashing Function (PHF) implementations in Rust. Provides secure and efficient solutions to protect passwords in applications and systems requiring robust storage and validation.
  * 🔧 **Main features:**

    * Password hashing implementations such as Argon2, bcrypt, and PBKDF2.
    * Optimized for security and resistance against brute-force attacks, using adjustable cost factors to increase security.
    * `no_std` compatible, suitable for embedded systems.
    * Easy integration in Rust projects, focusing on simplicity and security.
    * Actively maintained by RustCrypto community, providing secure and efficient password handling solutions.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/RustCrypto/password-hashes/tree/master)

* **rust-bcrypt**

  * 📚 **Description:** **rust-bcrypt** is a Rust implementation of bcrypt, a password hashing algorithm resistant to brute-force attacks. Widely used to protect stored passwords, bcrypt uses an adjustable cost factor to increase computation time and security.
  * 🔧 **Main features:**

    * Bcrypt implementation with adjustable cost factor to enhance security against dictionary and brute-force attacks.
    * Uses a random salt for each password, ensuring identical passwords produce different hashes.
    * Simple and secure interface for creating, verifying, and comparing password hashes.
    * `no_std` compatible, suitable for resource-constrained or embedded environments.
    * Actively maintained with regular updates to ensure security and efficiency.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/Keats/rust-bcrypt)

* **phpass**

  * 📚 **Description:** **phpass** is a PHP implementation of bcrypt and password hashing, designed to be lightweight and efficient. Uses bcrypt with a random salt to protect stored passwords. Provides an extra security layer, making dictionary and brute-force attacks much harder.
  * 🔧 **Main features:**

    * Bcrypt algorithm implementation for password hashing.
    * Supports creating and verifying passwords with a random salt, ensuring identical passwords have different hashes.
    * Configurable cost factor, allowing security adjustment against brute-force attacks based on available computational power.
    * Actively maintained with regular improvements to ensure security and efficiency.
    * Compatible with PHP applications of any size, from small websites to large-scale apps.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/clausehound/phpass)

* **RustCrypto/formats/pkcs5**

  * 📚 **Description:**
    **RustCrypto/formats/pkcs5** is an implementation of the PKCS #5 format standards for password management in Rust. PKCS #5 defines a format for password-based key derivation, which is fundamental for password cryptography security. This repository provides an efficient and secure implementation of these formats, including key derivation using functions like PBKDF2.
  * 🔧 **Main features:**

    * PBKDF2 implementation, a password-based key derivation algorithm using a repeat-function approach to protect passwords against dictionary attacks.
    * `no_std` compatible, allowing use in embedded systems or resource-constrained environments.
    * Provides a simple and secure interface for deriving keys from passwords in Rust applications.
    * Actively maintained by the RustCrypto community, focusing on the security and efficiency of cryptographic functions.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/RustCrypto/formats/tree/master/pkcs5)
* **rust-argon2**

  * 📚 **Description:**
    **rust-argon2** is a Rust implementation of the Argon2 key derivation function. Argon2 is a password hashing algorithm resistant to brute-force attacks, designed to be secure in resource-constrained environments. This implementation is designed to be efficient, flexible, and easy to use, allowing adjustment of computation time and memory usage to enhance security.
  * 🔧 **Main features:**

    * Implementation of the Argon2 key derivation algorithm with support for all three operation modes: Argon2d, Argon2i, and Argon2id.
    * Allows tuning of iterations, memory size, and parallelism to optimize resource usage and increase security.
    * Random "salt" function ensures identical passwords produce different hashes.
    * `no_std` compatible, suitable for embedded and resource-limited environments.
    * Actively maintained by the Rust community, focusing on security and flexibility.
  * 🌐 **Resources:**

    * [GitHub Repository](https://github.com/sru-systems/rust-argon2)

