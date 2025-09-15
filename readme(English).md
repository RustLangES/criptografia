# 🔐 **Applied Cryptography with Rust**  

🌟 A curated collection of tools, libraries, and resources in Rust for working with cryptography. Explore the power of Rust in the world of digital security and privacy! 🚀  

## 📖 **Why Rust for Cryptography?**  
Rust offers security, efficiency, and support for concurrent programming, making it an ideal language for building reliable and scalable cryptographic applications and tools. 💪  

With these resources, you can dive into the exciting world of cryptography and zero-knowledge proofs using Rust. 🚀  

---

## 🛠️ **Featured Libraries and Projects**
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
  * 📚 **Description:** PetraVM is a general-purpose virtual machine designed to be succinctly verified using the Binius proof system. Its execution model and ISA are optimized for efficient proofs with Binius, supporting recursive verification, general computation through WebAssembly, and high-performance verifiable computation with a proprietary language called PetraML.  
  * 🔧
