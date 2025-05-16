# 🔐 **Criptografía aplicable con Rust**  

🌟 Una colección curada de herramientas, bibliotecas y recursos en Rust para trabajar con criptografía. ¡Explora el poder de Rust en el mundo de la seguridad y privacidad digital! 🚀  

## 📖 **¿Por qué Rust para Criptografía?**  
Rust ofrece seguridad, eficiencia y soporte para programación concurrente, convirtiéndolo en un lenguaje ideal para construir aplicaciones y herramientas criptográficas confiables y escalables. 💪  

Con estos recursos, puedes adentrarte en el emocionante mundo de la criptografía y las pruebas de conocimiento cero utilizando Rust. 🚀  

---

## 🛠️ **Librerías y Proyectos Destacados**
* [Post-Quantum](https://github.com/RustLangES/criptografia/blob/main/README.md#post-quantum)
  * [Librerías de PQS](https://github.com/RustLangES/criptografia/blob/main/README.md#librer%C3%ADas-de-pqs)
* [ZKPs](https://github.com/RustLangES/criptografia/blob/main/README.md#zero-knowledge)
  * [IA-ZKML-ZKVM](https://github.com/RustLangES/criptografia/blob/main/README.md#ia-zkml-zkvm)
  * [Recurso Educativo](https://github.com/RustLangES/criptografia/blob/main/README.md#recurso-educativo)
  * [Librerías Avanzadas de ZKP](https://github.com/RustLangES/criptografia/blob/main/README.md#librer%C3%ADas-avanzadas-de-zkp)
  * [ZKTLS](https://github.com/RustLangES/criptografia/blob/main/README.md#zktls)
  * [Tools y Proyectos](https://github.com/RustLangES/criptografia/blob/main/README.md#tools-y-proyectos)
* [MPC](https://github.com/RustLangES/criptografia/blob/main/README.md#secure-multiparty-computation)
  * [Librerias de MPC](https://github.com/RustLangES/criptografia/blob/main/README.md#librerias-de-mpc)
  * [Frameworks de MPC](https://github.com/RustLangES/criptografia/blob/main/README.md#frameworks-de-mpc)
  * [MPC Tools](https://github.com/RustLangES/criptografia/blob/main/README.md#mpc_tools)
* [FHE](##Fully-Homomorphic-Encryption)
  * [Librerias de FHE](https://github.com/RustLangES/criptografia/blob/main/README.md#fully-homomorphic-encryption)
* [Hash Function](https://github.com/RustLangES/criptografia/blob/main/README.md#hash-function)
  * [Hash Functions and Friends](https://github.com/RustLangES/criptografia/blob/main/README.md#hash-functions-and-friends)
  * [Poseidon](https://github.com/RustLangES/criptografia/blob/main/README.md#poseidon)
  * [Password-Hashing-Functions](https://github.com/RustLangES/criptografia/blob/main/README.md#hash-functions-and-friends)

## Post-Quantum
### Librerías de PQS
* **Liboqs-rust**  
  * 📚 **Descripción:**  
    Liboqs-rust es un binding de Rust para la biblioteca iboqs, desarrollada por el proyecto Open Quantum Safe. Proporciona herramientas para experimentar e integrar algoritmos de criptografía poscuántica, diseñados para resistir ataques de computación cuántica.  

  * 🔧 **Características principales:**  
      - Soporte para algoritmos de firma digital y KEMs (Key Encapsulation Mechanisms) poscuánticos.  
      - Compatible con la biblioteca nativa en C, permitiendo una integración sencilla en proyectos basados en Rust.  
      - Enfocado en aplicaciones experimentales y de investigación en criptografía poscuántica.  
      - Compatible con una amplia gama de algoritmos aprobados y experimentales.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/open-quantum-safe/liboqs-rust)  

* **Kyber**  
  * 📚 **Descripción:**  
    Kyber es una implementación en Rust del algoritmo de cifrado poscuántico Kyber, que forma parte de los finalistas del proceso de estandarización de NIST para criptografía poscuántica. Este algoritmo está diseñado para proporcionar seguridad resistente a ataques de computación cuántica en la generación y el intercambio de claves.  

  * 🔧 **Características principales:**  
      - Basado en el esquema de criptografía de redes de retículas (lattice-based).  
      - Eficiente en términos de rendimiento y uso de recursos, adecuado para aplicaciones prácticas.  
      - Diseñado para garantizar confidencialidad y seguridad incluso frente a ataques de computación cuántica.  
      - Implementación en Rust para aprovechar su seguridad y rendimiento.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/Argyle-Software/kyber)  
      - [Documentación](https://pq-crystals.org/kyber/)  

* **Dilithium**  
  * 📚 **Descripción:**  
    Dilithium es una implementación en Rust del algoritmo de firma digital poscuántica CRYSTALS-Dilithium, uno de los esquemas seleccionados para estandarización por el NIST. Este esquema está basado en redes de retículas y diseñado para ofrecer seguridad frente a ataques de computación cuántica, manteniendo un equilibrio entre rendimiento, tamaño de firma y claves.  

  * 🔧 **Características principales:**  
      - Basado en criptografía de redes de retículas (lattice-based cryptography).  
      - Seguridad resistente a computación cuántica, ideal para aplicaciones futuras.  
      - Óptimo rendimiento en generación y verificación de firmas.  
      - Implementación en Rust para garantizar fiabilidad y seguridad del código.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/Argyle-Software/dilithium)  
      - [Documentación](https://pq-crystals.org/dilithium/)  

* **SPHINCS+**  
  * 📚 **Descripción:**  
    SPHINCS+ es una implementación en Rust del esquema de firma digital poscuántica SPHINCS+, diseñado para resistir ataques de computación cuántica. Este esquema se basa en árboles hash y es completamente libre de estructuras algebraicas, lo que lo hace altamente seguro y flexible para diversas aplicaciones.  

  * 🔧 **Características principales:**  
      - Basado en árboles hash (hash-based cryptography), sin estructuras algebraicas.  
      - Seguridad resistente a computación cuántica, ideal para escenarios futuros.  
      - Ofrece múltiples configuraciones que permiten equilibrar rendimiento, tamaño de firma y claves.  
      - Implementación en Rust para un alto nivel de seguridad y confiabilidad.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/Argyle-Software/sphincsplus)  
      - [Documentación](https://sphincs.org/)  
* **zkDilithium**  
  * 📚 **Descripción:**  
    zkDilithium es una implementación en Rust que combina el esquema de firma digital CRYSTALS-Dilithium con pruebas de conocimiento nulo  (ZKPs). Este enfoque innovador garantiza la autenticidad de las firmas mientras mantiene la privacidad de los datos, haciéndolo ideal para aplicaciones donde la confidencialidad y la seguridad son críticas.  

  * 🔧 **Características principales:**  
      - Basado en CRYSTALS-Dilithium, un esquema de firma digital resistente a ataques cuánticos.  
      - Integra pruebas de conocimiento nulo (ZKPs) para preservar la privacidad.  
      - Diseñado para proporcionar autenticidad y confidencialidad simultáneamente.  
      - Implementación en Rust para aprovechar su eficiencia y seguridad.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/guruvamsi-policharla/zkdilithium)
        
* **QuantCrypt**  
  * 📚 **Descripción:**  
    QuantCrypt es una implementación en Rust de una serie de algoritmos de criptografía post-cuántica, diseñada para ofrecer soluciones de seguridad resistentes a ataques de computación cuántica. La librería incluye una variedad de algoritmos criptográficos modernos adaptados para soportar las futuras amenazas que traerán las computadoras cuánticas.  

  * 🔧 **Características principales:**  
      - Soporta varios algoritmos de criptografía post-cuántica.  
      - Diseñada para ser modular y extensible, permitiendo la integración de nuevos algoritmos.  
      - Enfoque en rendimiento y eficiencia para aplicaciones reales.  
      - Implementación en Rust para aprovechar su seguridad y eficiencia.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/codespree/quantcrypt)
      - 
* **pqcrypto**  
  * 📚 **Descripción:**  
    pqcrypto es una librería en Rust que implementa una variedad de algoritmos criptográficos resistentes a la computación cuántica. Esta librería incluye soluciones para firmas digitales, intercambio de claves y cifrado, todas diseñadas para proteger los datos contra futuros avances en la computación cuántica.  

  * 🔧 **Características principales:**  
      - Soporta varios algoritmos de criptografía post-cuántica, incluidos cifrados y firmas.  
      - Ofrece soluciones robustas y eficientes para escenarios que requieren alta seguridad.  
      - Implementación en Rust, asegurando alta confiabilidad y eficiencia.  
      - Compatible con estándares y proyectos de criptografía post-cuántica.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/rustpq/pqcrypto)  
* **Citadel Protocol**  
  * 📚 **Descripción:**  
    Citadel Protocol es una solución de seguridad diseñada para proteger la comunicación entre sistemas distribuidos mediante el uso de criptografía avanzada. Este protocolo se centra en la autenticación mutua, el cifrado de extremo a extremo y la protección frente a amenazas externas, con especial atención a la resistencia ante ataques cuánticos.  

  * 🔧 **Características principales:**  
      - Autenticación mutua basada en criptografía avanzada.  
      - Cifrado de extremo a extremo para garantizar la privacidad de los datos.  
      - Resistencia a amenazas cuánticas, asegurando la seguridad futura de las comunicaciones.  
      - Implementación modular que permite adaptarse a diferentes entornos y requisitos de seguridad.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/Avarok-Cybersecurity/Citadel-Protocol)
* **KyberLib**  
  * 📚 **Descripción:**  
    KyberLib es una implementación en Rust de la biblioteca de criptografía basada en el algoritmo Kyber, uno de los algoritmos de cifrado post-cuántico más prometedores. Esta biblioteca proporciona una implementación eficiente y segura del algoritmo Kyber para aplicaciones que requieren resistencia contra los ataques de computación cuántica.  

  * 🔧 **Características principales:**  
      - Implementación eficiente del algoritmo de cifrado Kyber para un rendimiento óptimo.  
      - Diseñado para ser resistente a los ataques de computación cuántica.  
      - Implementación en Rust que asegura eficiencia y seguridad.  
      - Soporte para diversas configuraciones y tamaños de clave para adaptarse a diferentes necesidades.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/sebastienrousseau/kyberlib)  

* **faest-rs**  
  * 📚 **Descripción:**  
    faest-rs es una implementación en Rust del esquema de firma FAEST (Fast and Efficient Signature Scheme). Este esquema proporciona firmas digitales eficientes y seguras, adaptadas para resistir ataques cuánticos, utilizando técnicas modernas de criptografía basada en problemas matemáticos difíciles de resolver.  

  * 🔧 **Características principales:**  
      - Basado en el esquema FAEST para firmas digitales rápidas y seguras.  
      - Diseñado para ser resistente a los ataques de computación cuántica.  
      - Implementación en Rust para aprovechar su eficiencia y seguridad.  
      - Permite realizar verificaciones de firma de manera eficiente y escalable.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/ait-crypto/faest-rs)  


## Zero-Knowledge
📖 **¿Qué son las Pruebas de Conocimiento Cero (ZKPs)?**

Las **pruebas de conocimiento cero** son un tipo de protocolo criptográfico que permite a una parte (el "prover") demostrar que posee cierta información sin revelar la información en sí misma. Las ZKPs son fundamentales para aplicaciones que requieren alta seguridad y privacidad, como la verificación de transacciones en blockchain sin comprometer la confidencialidad de los datos.

### IA-ZKML-ZKVM
-------
* **EZKL**  
  * 📚 **Descripción:** EZKL permite la verificación de modelos de IA y análisis utilizando pruebas de conocimiento cero (ZKPs) sin exponer datos sensibles. Soporta modelos en formato ONNX y automatiza la generación de pruebas, facilitando la integración de ZKPs en aplicaciones de IA/ML.  
  * 🔧 **Características principales:**  
      - Compatible con Python, JavaScript, Rust, y CLI.  
      - Generación automatizada de pruebas sin necesidad de experiencia en criptografía.  
      - Utiliza **Lilith**, un clúster de computación en la nube, para pruebas a gran escala.  
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/zkonduit/ezkl)  
    - [Sitio Web](https://ezkl.xyz/)  
    - [Documentación](https://docs.ezkl.xyz/)

* **ProveKit (WorldCoin)**
  *  **📚 Descripción:** ProveKit es una herramienta de código abierto diseñada para facilitar la implementación y verificación de pruebas criptográficas avanzadas. Desarrollada por World Foundation, esta biblioteca tiene como objetivo simplificar la creación de sistemas seguros que utilicen técnicas como pruebas de conocimiento cero (ZKP) o circuitos garbled, permitiendo a los desarrolladores proteger datos sensibles y validar computations sin comprometer la privacidad.
  *  **🔧 Características principales:**
     * Soporte para la generación y verificación de pruebas de conocimiento cero (Zero-Knowledge Proofs).
     * Integración con protocolos de computación multipartita (MPC) para cálculos seguros.
     * Herramientas de alto nivel para construir aplicaciones con privacidad garantizada.
     * Compatible con lenguajes como Rust o Python, enfocado en rendimiento y seguridad.
     * Documentación detallada para facilitar su adopción en proyectos reales.
  *  **🌐 Recursos:**
     * [Repositorio GitHub](https://github.com/worldfnd/ProveKit) 

* **Mopro**
  * **📚 Descripción:** Mopro es una biblioteca de código abierto diseñada para facilitar la integración de pruebas criptográficas avanzadas en aplicaciones móviles. Desarrollada por zkMoPro, esta herramienta permite a los desarrolladores implementar pruebas de conocimiento cero (ZKP) de manera eficiente, protegiendo datos sensibles y habilitando computaciones seguras sin comprometer la privacidad, con un enfoque especial en plataformas móviles como iOS y Android.
  * **🔧 Características principales:**
    * Soporte para la generación y verificación de pruebas de conocimiento cero (Zero-Knowledge Proofs) en dispositivos móviles.
    * Integración optimizada para plataformas móviles, con bindings en Rust y compatibilidad con iOS/Android.
    * Herramientas de alto nivel para construir aplicaciones con privacidad garantizada en entornos móviles.
    * Enfocado en rendimiento y seguridad, aprovechando la potencia de lenguajes como Rust.
    * Documentación detallada y ejemplos para facilitar su adopción en proyectos reales.
  * **🌐 Recursos:**
    * [Repositorio GitHub](https://github.com/zkmopro/mopro)
    * [Documentación](https://zkmopro.org/docs/intro)

* **Powdr**
  * 📚 **Descripción:** Powdr es una herramienta diseñada para facilitar la construcción de máquinas virtuales de conocimiento cero (zkVMs) y marcos de prueba similares. Su objetivo principal es mejorar la productividad, seguridad y rendimiento en el desarrollo de estas tecnologías. 

  * 🔧 **Características principales:**

     *  Modular y extensible, ideal para construir zkVMs personalizadas.
     *   Soporte para backends como Plonky3, Halo2 y eSTARK.
     *   Transparencia en la compilación, con artefactos legibles e inspeccionables.
     *   Automatización completa de la generación de pruebas y testigos.

  * 🌐 **Recursos:**  
     - [Documentación](https://docs.powdr.org/)  
     - [Repositorio GitHub](https://github.com/powdr-labs/powdr?utm_source=chatgpt.com) 

* **OpenVM**  
  * 📚 **Descripción:** Un marco zkVM modular y extensible diseñado para personalización y compatibilidad con pruebas avanzadas. Permite ejecutar programas de longitud ilimitada, realizar pruebas on-chain, y soportar extensiones como ECDSA y aritmética modular.  
  * 🔧 **Características principales:**  
    *  Pruebas de programas Rust de longitud ilimitada.  
    *  Verificación on-chain.  
    * Extensiones avanzadas para pruebas personalizadas.  
* 🌐 **Recursos:**  
  - [Blog](https://blog.axiom.xyz/openvm)  
  - [Repositorio GitHub](https://github.com/openvm-org/openvm)  
 * **Delphinus zkWASM**  
  * 📚 **Descripción:** zkWASM es una máquina virtual de conocimiento cero diseñada para ejecutar WASM (WebAssembly) con soporte para pruebas de conocimiento cero. Proporciona una infraestructura eficiente y escalable para aplicaciones que requieren privacidad y verificación criptográfica.  
  * 🔧 **Características principales:**  
    * Compatible con WASM para ejecutar aplicaciones comunes en entornos ZK.  
    * Herramientas avanzadas para generar pruebas de conocimiento cero en WASM.  
    * Escalabilidad optimizada para aplicaciones de alto rendimiento.  
  * 🌐 **Recursos:**  
     - [Sitio web](https://delphinuslab.com/zk-wasm/)  
     - [Repositorio GitHub](https://github.com/DelphinusLab/zkWasm)  

* **zkMove**  
  * 📚 **Descripción:** zkMove es una máquina virtual basada en bytecode diseñada para utilizar el lenguaje Move, proporcionando capacidades avanzadas para pruebas de conocimiento cero y ejecución segura en entornos blockchain.  
  * 🔧 **Características principales:**  
    * Soporte para pruebas de conocimiento cero en bytecode de Move.  
    * Alta eficiencia en la ejecución de contratos inteligentes basados en Move.  
    * Optimización para entornos blockchain escalables y seguros.  
  * 🌐 **Recursos:**  
     - [Sitio web](https://www.zkmove.net/)  
     - [Repositorio GitHub](https://github.com/young-rocks/zkmove)  

* **zkRiscV**  
  * 📚 **Descripción:** zkRiscV es una máquina virtual basada en el conjunto de instrucciones RV32I de RISC-V. Diseñada para ejecutar programas con pruebas de conocimiento cero, ofrece compatibilidad con uno de los conjuntos de instrucciones más utilizados en hardware.  
  * 🔧 **Características principales:**  
    * Compatible con el conjunto de instrucciones RV32I de RISC-V.  
    * Ideal para crear y ejecutar programas de conocimiento cero.  
    * Infraestructura eficiente y personalizable para desarrolladores avanzados.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/lucasgleba/zkRiscV)  

* **OlaVM**  
  * 📚 **Descripción:** OlaVM es una máquina virtual de conocimiento cero compatible con Ethereum. Permite a los desarrolladores ejecutar contratos inteligentes con privacidad avanzada utilizando tecnología ZK.  
  * 🔧 **Características principales:**  
    * Totalmente compatible con la máquina virtual de Ethereum (EVM).  
    * Proporciona privacidad y verificación criptográfica en contratos inteligentes.  
    * Enfoque optimizado para aplicaciones descentralizadas avanzadas.  
  * 🌐 **Recursos:**  
     - [Sitio web](https://olavm.org/)
     - [Repositorio Github](https://github.com/Sin7Y/olavm)

* **Tritron VM**  
  * 📚 **Descripción:** Triton VM es una máquina virtual de conocimiento cero diseñada para maximizar la eficiencia de las pruebas criptográficas. Ideal para aplicaciones que requieren operaciones rápidas y escalables.  
  * 🔧 **Características principales:**  
    * Optimización para pruebas criptográficas de alta velocidad.  
    * Arquitectura modular y personalizable.  
    * Compatible con diversos entornos blockchain.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/TritonVM/triton-vm)  

* **Risc0**  
  * 📚 **Descripción:** Risc0 es una máquina virtual de propósito general basada en RISC-V que integra tecnología ZK para pruebas de conocimiento cero. Es ideal para ejecutar programas con privacidad avanzada en cualquier contexto.  
  * 🔧 **Características principales:**  
    * Soporte para el conjunto de instrucciones RISC-V.  
    * Funcionalidad de conocimiento cero generalizada para múltiples aplicaciones.  
    * Diseño modular para flexibilidad en implementación y desarrollo.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/risc0/risc0)  

* **Miden VM**  
  * 📚 **Descripción:** Miden VM es una máquina virtual basada en STARKs diseñada para proporcionar pruebas de conocimiento cero con alta escalabilidad y rendimiento. Está respaldada por Polygon y es ideal para aplicaciones blockchain modernas.  
  * 🔧 **Características principales:**  
    * Basada en tecnología STARK para pruebas rápidas y seguras.  
    * Escalabilidad optimizada para grandes volúmenes de datos.  
    * Arquitectura avanzada para soportar múltiples casos de uso blockchain.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/0xPolygonMiden/miden-vm)  

* **Valida**  
  * 📚 **Descripción:** Valida es una máquina virtual de conocimiento cero con un frontend basado en LLVM. Está diseñada para facilitar la construcción de pruebas ZK de manera eficiente y accesible para desarrolladores.  
  * 🔧 **Características principales:**  
    * Integración con LLVM para soporte avanzado de compilación.  
    * Compatible con múltiples lenguajes y entornos de desarrollo.  
    * Ideal para aplicaciones que requieren verificación criptográfica flexible.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/delendum-xyz/valida)
   
* **Succinct SP1**  
  * 📚 **Descripción:** SP1 es un sistema desarrollado por Succinct Labs que permite ejecutar máquinas virtuales completas dentro de contratos inteligentes de Ethereum, utilizando tecnología de pruebas de conocimiento cero para verificar la ejecución fuera de la cadena. Está diseñado para optimizar la computación dentro del ecosistema blockchain, proporcionando soluciones eficientes para aplicaciones complejas.  
  * 🔧 **Características principales:**  
    * Ejecución de máquinas virtuales completas dentro de contratos inteligentes en Ethereum.  
    * Uso de pruebas de conocimiento cero para verificar la ejecución fuera de la cadena.  
    * Compatibilidad con múltiples aplicaciones blockchain avanzadas.  
    * Escalabilidad optimizada para entornos con alta demanda computacional.  
    * Reducción de costos computacionales mediante la validación off-chain.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/succinctlabs/sp1)  
     - [Documentación oficial](https://docs.succinct.xyz/docs/introduction)  

* **Delphinus zkWasm**  
  * 📚 **Descripción:** zkWasm es una infraestructura desarrollada por Delphinus Lab que permite ejecutar programas WebAssembly (WASM) con verificación mediante pruebas de conocimiento cero. Combina la flexibilidad de WASM con la seguridad criptográfica de las zk-SNARKs, permitiendo validaciones off-chain eficientes y seguras dentro del ecosistema blockchain. Está orientado a facilitar el desarrollo de zkDApps y a mejorar la escalabilidad de aplicaciones descentralizadas complejas.  
  * 🔧 **Características principales:**  
    * Ejecución de programas WebAssembly (WASM) con verificación criptográfica.  
    * Uso de pruebas de conocimiento cero (zk-SNARKs) para validar cálculos fuera de la cadena.  
    * Soporte para múltiples lenguajes a través de compilación a WASM.  
    * Enfoque modular para integrarse con diferentes blockchains.  
    * Infraestructura optimizada para construir zkDApps de alto rendimiento.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/DelphinusLab/zkWasm)  
     - [Sitio web oficial](https://www.delphinuslab.com/)  
   

* **zkMIPS (ZKM)**  
  * 📚 **Descripción:** ZKM es una infraestructura general de cómputo verificable basada en la microarquitectura MIPS y en el sistema de pruebas de conocimiento cero **Plonky2**. Su objetivo es empoderar a Ethereum como capa de asentamiento global, permitiendo ejecutar programas complejos en lenguajes como Go y Rust y verificar su ejecución de forma eficiente mediante zk-SNARKs. ZKM facilita tanto la generación local de pruebas como el uso de una red de prueba dedicada (demo), con verificación compatible con la EVM para integraciones blockchain.  
  * 🔧 **Características principales:**  
    * Infraestructura de cómputo verificable construida sobre MIPS y Plonky2.  
    * Soporte para generación de pruebas en programas escritos en Go y Rust.  
    * Opciones de prueba local o a través de una red de pruebas (Proving Network).  
    * Plantilla de proyecto para generar pruebas compatibles con EVM y contratos de verificación on-chain.  
    * Integración directa con blockchains como Ethereum (ej. Sepolia).  
    * Proyecto en desarrollo activo con guías detalladas para pruebas y despliegue.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/zkMIPS/zkm)  
     - [Sitio web oficial / Registro](https://www.zkm.io/apply)  
     - [Guía de pruebas y documentación](https://docs.zkm.io/introduction/)  

* **Polygon ZisK**  
  * 📚 **Descripción:** ZisK es una máquina virtual de conocimiento cero (zkVM) desarrollada por Polygon, diseñada para ejecutar programas arbitrarios de forma verificable y sin confianza. Basada en tecnología zk avanzada como Plonky3 y sobre arquitectura RISC-V, ZisK permite a los desarrolladores generar y verificar pruebas criptográficas con eficiencia y flexibilidad. Está escrita principalmente en Rust y se enfoca en la facilidad de integración de pruebas ZK en aplicaciones escalables y privadas. Actualmente se encuentra en desarrollo activo y no debe utilizarse aún en entornos de producción.  
  * 🔧 **Características principales:**  
    * zkVM de alto rendimiento enfocada en pruebas verificables de programas arbitrarios.  
    * Soporte principal para Rust, con planes para añadir otros lenguajes.  
    * Basada en arquitectura RISC-V y tecnología Plonky3 para pruebas succinctas.  
    * Entorno de desarrollo amigable para integrar ZK en aplicaciones descentralizadas.  
    * Licenciamiento dual: Apache 2.0 o MIT.  
    * Proyecto en desarrollo activo — aún no apto para producción.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/0xPolygonHermez/zisk)  
     - [Documentación oficial](https://0xpolygonhermez.github.io/zisk/)  
      


### Recurso-Educativo
------
* **MyZKP**  
  * 📚 **Descripción:** Una implementación educativa en Rust de protocolos de Zero-Knowledge creada desde cero. Ideal para aprender y trabajar con pruebas ZK desde sus fundamentos.  
  * 🔧 **Características principales:**  
     * Diseño educativo para comprender los principios básicos de las ZKPs.  
     * Construcción paso a paso en Rust.  
  *  🌐 **Recursos:**  
      * [Repositorio GitHub](https://koukyosyumei.github.io/MyZKP/index.html)




### Librerías Avanzadas de ZKP
----------

* **Halo2**  
  * 📚 **Descripción:** Halo2 es una librería de pruebas de conocimiento cero que ofrece una arquitectura eficiente para zkSNARKs en Rust. Es particularmente conocida por su enfoque en la eficiencia y escalabilidad.  
  * 🔧 **Características principales:**  
    * Optimización de zkSNARKs utilizando el sistema de aritmética sobre curvas elípticas.  
    * Funcionalidad de pruebas de conocimiento cero con un alto rendimiento y bajo costo computacional.  
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/zcash/halo2)  
    - [Documentación](https://zcash.github.io/halo2/)

* **Plonky3**  
  * 📚 **Descripción:** Plonky3 es un conjunto de herramientas para implementar IOPs polinomiales (PIOPs), como PLONK y STARKs. Su objetivo es soportar varios esquemas de compromiso polinomial, como Brakedown.
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/Plonky3/Plonky3)
    - [Awesome Plonky3](https://github.com/Plonky3/awesome-plonky3)
  

* **Lambworks**  
  * 📚 **Descripción:** Es una biblioteca que implementa probadores SNARKs y STARKs, permitiendo la personalización de SNARKs. Ofrece primitivas criptográficas, alto rendimiento y herramientas fáciles de usar para trabajar con pruebas de conocimiento cero (ZKPs). Soporta diversos backends de pruebas y es compatible con diferentes frontends, orientándose a crear una librería eficiente y lista para producción.  
  * 🔧 **Características principales:**  
    * Implementación de SNARKs y STARKs.
    * Soporte para primitivas criptográficas.
    * Optimización de rendimiento.
    * Compatible con varios backends de pruebas.
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/lambdaclass/lambdaworks)  
    - [Documentación](https://lambdaclass.github.io/lambdaworks/)

* **Arkworks**  
  * 📚 **Descripción:** Es un conjunto de bibliotecas en Rust que proporciona herramientas para la construcción de criptografía de conocimiento cero (ZKPs) y SNARKs. Facilita la creación de pruebas eficientes y seguros para aplicaciones blockchain, soportando esquemas como PLONK, Marlin y otros. Ofrece funcionalidades avanzadas para polinomios, curvas elípticas y aritmética modular.
  * 🔧 **Características principales:**  
    * Implementaciones eficientes de campos finitos y curvas elípticas.
    * Sistemas SNARK como Groth16 y Marlin.
    * Herramientas para la creación de circuitos R1CS y algebra de polinomios.
    * Soporta el uso de pruebas universales y productos internos de pares.
    * Recursos para programación R1CS y pruebas de SNARK.
   * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/arkworks-rs)  
     - [Documentación](https://arkworks.rs/)

* **Binius**  
  * 📚 **Descripción:** Es una biblioteca optimizada en Rust diseñada para comprometer polinomios multilineales de manera eficiente. Binius está orientada a mejorar el rendimiento de las máquinas virtuales de conocimiento cero (ZKVM) y las pruebas criptográficas avanzadas, especialmente en arquitecturas de bits pequeños.  
  * 🔧 **Características principales:**  
    * Reducción significativa de los costos computacionales en esquemas de compromiso de polinomios.  
    * Compatible con máquinas virtuales de conocimiento cero para pruebas de alta eficiencia.  
    * Implementación optimizada para torres de campos binarios en arquitecturas de bajo nivel.  
    * Construido en Rust, aprovechando su seguridad y velocidad para operaciones críticas.  
    * Licencia Apache 2.0, adecuada para proyectos de código abierto y comerciales.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/IrreducibleOSS/binius)  
     - [Publicación técnica sobre Binius](https://www.irreducible.com/posts/better-faster-smaller-binius)
   
  * * **Bellman**  
  * 📚 **Descripción:** Bellman es una biblioteca de Rust que proporciona una implementación eficiente de zk-SNARKs para criptografía de conocimiento cero. Está diseñada para facilitar la construcción de aplicaciones que requieren pruebas de validez en blockchains, incluyendo esquemas de pruebas como Groth16 y sus optimizaciones. Bellman es conocida por su enfoque en la eficiencia y la escalabilidad, ofreciendo una interfaz que simplifica el desarrollo de sistemas criptográficos en blockchain.  
  * 🔧 **Características principales:**  
    * Implementación eficiente de zk-SNARKs, en particular el esquema Groth16.  
    * Optimización para pruebas rápidas y de bajo consumo computacional.  
    * Soporte para estructuras algebraicas avanzadas como curvas elípticas.  
    * Compatible con aplicaciones que requieren pruebas de validez en blockchains.  
    * Enfoque en la escalabilidad y la eficiencia de la ejecución.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub](https://github.com/zkcrypto/bellman)  
     - [Documentación oficial](https://docs.rs/bellman/)  
* **Spartan**  
  * 📚 **Descripción:** Spartan es una plataforma de Microsoft para la creación y verificación de pruebas de conocimiento cero (ZKPs). Está diseñada para ser flexible y eficiente, permitiendo a los desarrolladores implementar ZKPs en diversas aplicaciones, especialmente en entornos blockchain. Spartan proporciona un conjunto de herramientas que permite la optimización de recursos en la ejecución de pruebas criptográficas, facilitando su integración en sistemas descentralizados.  
  * 🔧 **Características principales:**  
    * Plataforma flexible para la creación de ZKPs.  
    * Optimización de recursos computacionales en la ejecución de pruebas.  
    * Compatible con aplicaciones blockchain y sistemas descentralizados.  
    * Herramientas para la creación y verificación de pruebas criptográficas a gran escala.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub de Spartan](https://github.com/microsoft/Spartan)  
   
 * **Spartan2**  
  * 📚 **Descripción:** Spartan2 es una herramienta desarrollada por Microsoft que proporciona una plataforma para realizar pruebas de conocimiento cero (ZKPs) de manera eficiente. Está diseñada para integrarse en sistemas de blockchain y permitir la construcción de aplicaciones descentralizadas mediante pruebas criptográficas. Spartan2 mejora la eficiencia de las pruebas y optimiza el uso de recursos para aplicaciones que requieren pruebas de validez a gran escala.  
  * 🔧 **Características principales:**  
    * Implementación de ZKPs con un enfoque en la eficiencia de las pruebas.  
    * Optimización para minimizar el uso de recursos computacionales y mejorar la escalabilidad.  
    * Herramientas para realizar pruebas de validez en aplicaciones de blockchain.  
    * Integración fácil con aplicaciones descentralizadas y plataformas blockchain.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub de Spartan2](https://github.com/microsoft/Spartan2)  

* **Bulletproofs**  
  * 📚 **Descripción:** Bulletproofs es un esquema de prueba de conocimiento cero (ZKP) eficiente y sin confianza en el sistema de verificación. Proporciona pruebas de rango de forma compacta y eficientes, optimizando las pruebas criptográficas sin necesidad de configuraciones confiables. Bulletproofs se utiliza ampliamente en aplicaciones de blockchain y criptomonedas para garantizar la privacidad y la integridad sin comprometer el rendimiento.  
  * 🔧 **Características principales:**  
    * Pruebas compactas de rango sin necesidad de configuraciones confiables.  
    * Optimización de la eficiencia criptográfica.  
    * Aceleración de pruebas para aplicaciones blockchain.  
    * Ideal para entornos con altos requisitos de privacidad y escalabilidad.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub de Bulletproofs](https://github.com/dalek-cryptography/bulletproofs)  
     - [Documentación oficial](https://dalekcryptography.github.io/bulletproofs/)

* **Plonk**  
  * 📚 **Descripción:** Plonk es un sistema de prueba de conocimiento cero eficiente y universal que permite verificar cualquier computación en un esquema criptográfico sin comprometer la seguridad o la confianza. Plonk utiliza un esquema de aritmética sobre campos finitos y es ampliamente utilizado en blockchain para ofrecer pruebas rápidas y escalables sin comprometer la privacidad.  
  * 🔧 **Características principales:**  
    * Sistema de prueba eficiente basado en la aritmética de campos finitos.  
    * Pruebas universales sin requerir configuraciones confiables.  
    * Soporta una amplia variedad de aplicaciones y casos de uso en blockchain.  
    * Alta escalabilidad y velocidad en comparación con otros esquemas de ZKP.  
  * 🌐 **Recursos:**  
     - [Repositorio GitHub de Plonk](https://github.com/dusk-network/plonk)  
     - [Documentación oficial](https://dusk-network.github.io/plonk/)

* **Jellyfish**  
  * 📚 **Descripción:**  
    Jellyfish es una biblioteca en Rust desarrollada por Espresso Systems que implementa el sistema de pruebas de conocimiento cero PLONK y sus extensiones.  

  * 🔧 **Características principales:**  
    * Implementación completa de PLONK y extensiones.  
    * Modularidad y flexibilidad para diferentes casos de uso.  
    * Optimización para generación y verificación rápidas de pruebas.  
    * Compatible con entornos que requieren privacidad y escalabilidad.  

  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/EspressoSystems/jellyfish)

* **Nova**  
  * 📚 **Descripción:**  
    Nova es un SNARK recursivo de alta velocidad, un sistema criptográfico que permite a un demostrador probar una afirmación matemática a un verificador con una prueba corta y verificación sucinta. Nova permite la ejecución de cálculos de manera incremental y verificable (IVC), lo que significa que un demostrador puede actualizar su prueba para incluir pasos adicionales de un cómputo sin necesidad de recalcular la verificación completa.  
    Este enfoque tiene aplicaciones en Rollups, funciones de retardo verificables (VDF), cadenas de bloques sucintas y máquinas de estado verificables.

  * 🔧 **Características principales:**  
      - Proveedor más rápido entre los sistemas recursivos conocidos.  
      - Circuito de verificación constante con aproximadamente 10,000 puertas de multiplicación.  
      - Implementado con un esquema de plegado criptográfico que reduce la verificación de dos afirmaciones NP a una sola.  
      - Aplicaciones en Rollups, VDFs, y ejecución de máquinas virtuales como EVM y RISC-V.  

  * 🌐 **Recursos:**  
      - [Repositorio GitHub](https://github.com/microsoft/Nova)  

### ZKTLS

* **TLSNotary**  
  * 📚 **Descripción:**  TLSNotary es un protocolo y herramienta de código abierto que permite realizar auditorías criptográficas de sesiones TLS, proporcionando pruebas verificables de las comunicaciones realizadas entre un cliente y un servidor sin comprometer la privacidad del cliente.    

  * 🔧 **Características principales:**  
    * Generación de pruebas criptográficas de sesiones TLS.
    *  Privacidad garantizada para el cliente durante el proceso de auditoría.
    *  Compatible con una amplia gama de aplicaciones y servicios web.
    *  Ideal para casos de uso que requieren transparencia y verificabilidad, como auditorías financieras o legales.
    *   Implementado en Python, con enfoque en accesibilidad y facilidad de uso.  

  * 🌐 **Recursos:**  
    -  [Repositorio GitHub](https://github.com/tlsnotary/tlsn)  
    - [Documentación oficial](https://docs.tlsnotary.org/)

### Tools-y-Proyectos
* **zkemail**  
  * 📚 **Descripción:** zkemail es un proyecto centrado en garantizar la comunicación segura y privada por correo electrónico utilizando pruebas de conocimiento nulo (ZKPs).  
  * 🔧 **Características principales:**  
    * Comunicación por correo electrónico segura mediante métodos criptográficos avanzados.  
    * Utiliza pruebas de conocimiento nulo para mantener la privacidad del usuario.  
  * 🌐 **Recursos:**  
    - [Sitio oficial](https://prove.email)  
    - [Repositorio en GitHub](https://github.com/zkemail)  
    - [Twitter](https://twitter.com/zkemail)  
** **mopro**
  * 📚 **Descripción:** Mopro es una biblioteca optimizada para pruebas de conocimiento cnulo (ZK) en dispositivos móviles. Se integra con Circom y Halo2, mejorando el rendimiento significativamente en comparación con soluciones tradicionales como `snarkjs`. Su objetivo es facilitar el desarrollo de aplicaciones ZK en plataformas móviles.
  * 🔧 **Características principales:**  
    * Integración con Circom y Halo2.
    * Rendimiento optimizado para dispositivos móviles.
    * Simplificación en el desarrollo de aplicaciones ZK.
  * 🌐 **Recursos:**  
    - [Repositorio GitHub de mopro](https://github.com/zkmopro/mopro)



-----------
## Secure-Multiparty-Computation
-----------
### Librerias-de-MPC
* **Swanky**  
  * 📚 **Descripción:** Swanky es una librería diseñada para facilitar el desarrollo de protocolos de Cómputo Multi-Partido (MPC). Ofrece herramientas para implementar esquemas de intercambio seguro de datos y operaciones computacionales entre múltiples partes, manteniendo la privacidad de los datos.  
  * 🔧 **Características principales:**  
    * Implementación modular y flexible para experimentación con protocolos MPC.
    * Soporte para esquemas como Garbled Circuits (GC) y Oblivious Transfer (OT).
    * Enfocado en ofrecer una base sólida para desarrolladores interesados en investigación y producción de soluciones basadas en MPC.
  * 🌐 **Recursos:**  
     - [Repositorio GitHub de Swanky](https://github.com/GaloisInc/swanky)  
* **Smol-MPC**  
  * 📚 **Descripción:** Smol-MPC es una librería ligera y eficiente para implementar protocolos de Cómputo Multi-Partido (MPC). Diseñada por HashCloak, esta librería se enfoca en brindar una solución simple, flexible y optimizada para realizar cálculos colaborativos de forma segura y privada entre múltiples participantes.
  * 🔧 **Características principales:**  
    * Compatibilidad con protocolos básicos de MPC, permitiendo operaciones colaborativas sin comprometer la privacidad de los datos.
    * Ligera y fácil de integrar en proyectos, ideal para quienes buscan una librería MPC accesible para experimentación o aplicaciones más pequeñas.
    * Enfocada en ser minimalista, por lo que es una excelente opción para desarrolladores que buscan comenzar con MPC sin complejidades innecesarias.
  * 🌐 **Recursos:**  
     - [Repositorio GitHub de smol-mpc](https://github.com/hashcloak/smol-mpc)  
     - [Documentación](https://docs.rs/smol-mpc/)

* **MPZ**  
  * 📚 **Descripción:**   MPZ es una colección de bibliotecas de computación multipartita (MPC) escritas en Rust 🦀. El proyecto tiene como objetivo proporcionar software MPC seguro, eficiente, modular y portátil, con un enfoque en la usabilidad.

  * ⚠️ **Aviso:**  Este proyecto está en desarrollo activo y no debe utilizarse en producción. Puede haber errores y cambios importantes frecuentes. Úselo bajo su propio riesgo.

  * 🔧 **Características principales:**  
    * Implementación de primitivas base para computación segura en entornos descentralizados.

    * DSL para crear circuitos booleanos de manera declarativa, diseñado para computación multipartita.

    * Implementación de protocolos OT fundamentales para garantizar la privacidad en operaciones de computación segura.

    * Soporte para conversiones eficientes entre diferentes tipos de compartidos para operaciones seguras.
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/privacy-scaling-explorations/mpz)  
   

### Frameworks-de-MPC
   
* **stoffelMPC**  
  * 📚 **Descripción:** StoffelMPC es un marco de trabajo para cómputo multi-partido (MPC, por sus siglas en inglés). Permite a los desarrolladores escribir software de MPC en un lenguaje específico de dominio que abstrae los detalles internos de los protocolos de MPC.

Estos programas de MPC se compilan a bytecode para el StoffelVM, que es una máquina virtual que permite ejecutarlos en un entorno multi-partido. Nuestra implementación se enfoca en protocolos MPC robustos, ya que estos son interesantes en el contexto de MPC como una sidechain. Esto significa que el MPC se utiliza para proporcionar la capa de privacidad que actualmente falta en las blockchains públicas.
  * 🔧 **Características principales:**  
    * Permite escribir programas en un lenguaje específico de dominio, simplificando el desarrollo de cómputo multi-partido.
    * Los programas se compilan a bytecode para ser ejecutados en StoffelVM, una máquina virtual especializada.
    * Enfocado en protocolos robustos, ideales para aplicaciones que requieren alta seguridad y fiabilidad.
    * Proporciona una capa de privacidad para blockchains públicas, protegiendo datos y transacciones.  
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/hashcloak/stoffelMPC)  
--------------------- 

### MPC_Tools

* **Garble-lang**  
  * 📚 **Descripción:** Garble-lang es un lenguaje de programación simple especializado en la computación segura y en la ejecución de cálculos sobre datos cifrados utilizando circuitos garbled. Su objetivo es permitir que los desarrolladores implementen aplicaciones privadas mediante computación multipartita (MPC), protegiendo la privacidad de los datos sin necesidad de descifrarlos.  
  * 🔧 **Características principales:**  
    * Lenguaje de alto nivel para construir y ejecutar circuitos de computación garbled.  
    * Permite realizar cálculos de manera segura sobre datos cifrados, sin revelar información sensible.  
    * Facilita la creación de aplicaciones que requieren privacidad, como contratos inteligentes y análisis de datos privados.  
    * Proporciona herramientas para la integración con otros protocolos de computación segura y privacidad.  
    * Ofrece un marco eficiente para la implementación de MPC.
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/sine-fdn/garble-lang)  
    - [Documentación](https://garble-lang.org)

- Tandem

  - **📚 Descripción:** Tandem es un motor de computación multipartita (MPC) de código abierto, seguro y maliciosamente robusto, diseñado para ser integrable y accesible. Su objetivo es permitir que las empresas y desarrolladores realicen cálculos colaborativos sobre datos cifrados utilizando circuitos garbled, protegiendo la privacidad sin necesidad de revelar la información subyacente. Desarrollado por la SINE Foundation, Tandem transforma los datos sensibles en oportunidades de valor mediante criptografía avanzada.
    - **🔧 Características principales:**
    - Motor de alto rendimiento para ejecutar circuitos garbled en computación bipartita segura.
    - Permite cálculos sobre datos cifrados sin comprometer la privacidad de las partes involucradas.
    - Facilita aplicaciones prácticas que requieren confidencialidad, como análisis de datos conjuntos y colaboración segura entre organizaciones.
    - Incluye herramientas como un servidor HTTP, un cliente CLI y soporte para WebAssembly, además de integración con Garble, un lenguaje de alto nivel para MPC.
    - Ofrece un marco eficiente y fácil de usar para implementar computación multipartita en escenarios reales.
  - **🌐 Recursos:**
    - [Repositorio GitHub](https://github.com/sine-fdn/tandem)
    - [Sitio web de SINE Foundation](https://sine.foundation/tandem)

## Fully-Homomorphic-Encryption
---------------------
### Librerias-de-FHE

* **tfhe-rs**  
  * 📚 **Descripción:** Tfhe-rs es una biblioteca en Rust que implementa la encriptación homomórfica totalmente funcional (TFHE, por sus siglas en inglés). Proporciona una forma eficiente y segura de realizar operaciones en datos cifrados, lo que permite el procesamiento de información sensible sin necesidad de descifrarla.  
  * 🔧 **Características principales:**  
    * Implementación de encriptación homomórfica totalmente funcional (TFHE).  
    * Permite realizar operaciones aritméticas y lógicas en datos cifrados.  
    * Alta eficiencia en el procesamiento de datos cifrados.  
    * Compatible con aplicaciones de privacidad y computación segura.  
    * Facilita el desarrollo de soluciones para la protección de datos y privacidad en entornos descentralizados.  
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/zama-ai/tfhe-rs)  
    - [Documentación](https://docs.zama.ai/tfhe-rs)

* **Openfhe-rs**  
  * 📚 **Descripción:** Es una implementación en Rust de OpenFHE, un marco de trabajo de encriptación homomórfica (FHE) de código abierto. Permite realizar operaciones sobre datos cifrados sin necesidad de descifrarlos, manteniendo la privacidad de los datos durante el procesamiento. OpenFHE es una tecnología emergente que es clave para aplicaciones de privacidad y computación segura en entornos de confianza.  
  * 🔧 **Características principales:**  
    * Implementación de encriptación homomórfica en Rust.
    * Soporta una amplia variedad de operaciones en datos cifrados sin necesidad de descifrarlos.
    * Basado en OpenFHE, un marco de trabajo conocido por su seguridad y flexibilidad.
    * Permite a los desarrolladores crear aplicaciones que protejan la privacidad de los datos durante su procesamiento.
    * Compatible con múltiples métodos de encriptación homomórfica avanzados.
    * Optimizado para aplicaciones que requieren computación segura y protección de datos.
    * Diseño modular y extensible para integrarse fácilmente en diferentes proyectos.
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/fairmath/openfhe-rs)  
    - [Documentación](https://openfhe-rust-wrapper.readthedocs.io/en/latest/)

* **Phantom-Zone**  
  * 📚 **Descripción:** Phantom-Zone es una librería que permite la construcción de protocolos de Cómputo Multi-Partido (MPC) de forma eficiente y segura. Desarrollada por Gauss Labs, esta herramienta está diseñada para ser escalable y aplicable a entornos de alta privacidad. Se centra en proporcionar implementaciones robustas para la ejecución de cálculos colaborativos sin comprometer la seguridad de los datos involucrados. 
  * 🔧 **Características principales:**  
    * Utiliza encriptación homomórfica totalmente multiplicativa para cálculos sobre entradas privadas de múltiples partes.
    * Ofrece dos tipos de protocolos de multi-partido: uno no interactivo y otro interactivo.
    * Permite realizar operaciones aritméticas y comparaciones en números enteros sin signo de 8 bits (FheUint8), con manejo de sobrecarga y errores de división por cero.
    * La librería se encuentra en etapa experimental y no debe utilizarse en producción para manejar datos sensibles debido a la falta de auditoría de seguridad.
 * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/gausslabs/phantom-zone)
   
## Hash-Function
### Hash-Functions-and-Friends
* **RustCrypto/hashes**  
  * 📚 **Descripción:**  
    RustCrypto/hashes es un conjunto de implementaciones de funciones hash criptográficas desarrolladas en Rust. Este repositorio incluye soporte para una variedad de algoritmos de hash ampliamente utilizados, diseñados para ser seguros y eficientes. Es una herramienta esencial para proyectos que requieren integridad de datos, verificación de firmas digitales y aplicaciones criptográficas.  
  * 🔧 **Características principales:**  
    * Implementaciones seguras y en constante desarrollo de funciones hash como SHA-2, SHA-3, Blake2, y más.
    * Compatibilidad con algoritmos hash autenticados como Poly1305.
    * Diseño modular para facilitar su integración en otros proyectos de Rust.
    * Enfoque en el rendimiento y la seguridad mediante la optimización de código y el uso de pruebas exhaustivas.
    * Totalmente compatible con el estándar `no_std`, permitiendo su uso en entornos de recursos limitados.
    * Activo y mantenido por la comunidad de RustCrypto, con contribuciones regulares y soporte para las últimas actualizaciones del lenguaje Rust.
   
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/gausslabs/phantom-zone)

* **BLAKE3**  
  * 📚 **Descripción:**  
    BLAKE3 es una función hash criptográfica moderna diseñada para ser rápida, segura y altamente paralelizable. Desarrollada por el equipo de BLAKE3, esta implementación combina las mejores características de algoritmos como BLAKE2, SHA-3 y Merkle-Damgård, ofreciendo un rendimiento excepcional en una variedad de plataformas, desde dispositivos móviles hasta servidores de alto rendimiento.  
  * 🔧 **Características principales:**  
    * Más rápida que las funciones hash SHA-2 y SHA-3 en la mayoría de los entornos.
    * Diseñada para ser altamente paralelizable y escalar en hardware multinúcleo y SIMD.
    * Soporta hashing incremental, hashing de claves y derivación de claves.
    * Construida sobre un diseño seguro que utiliza un árbol Merkle, permitiendo hashing eficiente en grandes cantidades de datos.
    * Implementaciones disponibles en múltiples lenguajes, incluyendo Rust, C, Python y más.
    * Auditada y respaldada por una amplia comunidad de desarrolladores.  
  * 🌐 **Recursos:**  
    - [Repositorio GitHub](https://github.com/BLAKE3-team/BLAKE3)
     
* **RustCrypto/KDFs**  
  * 📚 **Descripción:**  
    RustCrypto/KDFs es una colección de implementaciones de funciones de derivación de claves (Key Derivation Functions, KDFs) desarrolladas en Rust. Este repositorio incluye soporte para algoritmos ampliamente utilizados en aplicaciones criptográficas que requieren generar claves seguras a partir de entradas como contraseñas o claves maestras. Está diseñado para ofrecer seguridad, eficiencia y facilidad de integración en proyectos de Rust.  
  * 🔧 **Características principales:**  
    * Soporte para algoritmos KDF como HKDF (HMAC-based Extract-and-Expand Key Derivation Function) y PBKDF2 (Password-Based Key Derivation Function 2).
    * Diseñado para ser seguro y eficiente, con un enfoque en el rendimiento.
    * Compatible con el estándar `no_std`, permitiendo su uso en entornos de recursos limitados.
    * Modular y fácil de integrar en aplicaciones Rust que requieren generación de claves derivadas.
    * Mantenido por la comunidad de RustCrypto, con contribuciones regulares y pruebas exhaustivas para garantizar su confiabilidad.  
  * 🌐 **Recursos:** 
    - [Repositorio GitHub](https://github.com/RustCrypto/KDFs)

* **RustCrypto/universal-hashes**  
  * 📚 **Descripción:**  
    RustCrypto/universal-hashes es una colección de implementaciones de funciones hash universales desarrolladas en Rust. Estas funciones hash son utilizadas principalmente como bloques básicos en la construcción de algoritmos criptográficos, como códigos de autenticación de mensajes (MACs) y cifrados autenticados (AEAD).  
  * 🔧 **Características principales:**  
    * Implementaciones de funciones hash universales como Poly1305 y GHASH (utilizado en Galois/Counter Mode, GCM).
    * Diseñado para ser seguro, eficiente y fácil de integrar en aplicaciones Rust.
    * Compatible con el estándar `no_std`, lo que lo hace ideal para sistemas con recursos limitados.
    * Modular y compatible con otros componentes de RustCrypto, permitiendo una integración fluida en proyectos criptográficos.
    * Mantenido activamente por la comunidad de RustCrypto, con un enfoque en la seguridad y el rendimiento.  
  * 🌐 **Recursos:** 
    - [Repositorio GitHub](https://github.com/RustCrypto/universal-hashes)

 * **tiny-keccak**  
   * 📚 **Descripción:**  
    **tiny-keccak** es una implementación minimalista y eficiente de la función hash Keccak en Rust, que también es la base del estándar SHA-3. Diseñado para ser liviano y fácil de usar, es ideal para aplicaciones donde se requiere un algoritmo hash seguro y de alto rendimiento en entornos con recursos limitados.  
   * 🔧 **Características principales:**  
     * Soporte para Keccak y SHA-3, incluyendo variantes como SHAKE (Extendable-Output Functions, XOFs).
     * Implementación ligera y optimizada para un bajo consumo de recursos.
     * Compatible con el estándar `no_std`, permitiendo su uso en sistemas embebidos.
     * Fácil integración en proyectos de Rust gracias a su diseño modular y documentación clara.
    * Mantenido por la comunidad de Rust, con un enfoque en la simplicidad y la seguridad.  
  * 🌐 **Recursos:** 
    - [Repositorio GitHub](https://github.com/debris/tiny-keccak)
   
### Poseidon
* **Poseidon252**  
  * 📚 **Descripción:**  
    **Poseidon252** es una implementación altamente eficiente de la función hash Poseidon, desarrollada por el equipo de Dusk Network en Rust. Poseidon es una función hash optimizada para circuitos zk-SNARKs y zk-STARKs, utilizada principalmente en aplicaciones de criptografía avanzada, como la privacidad y las pruebas de conocimiento cero.  
  * 🔧 **Características principales:**  
    * Implementación de Poseidon sobre el campo escalar de 252 bits, ideal para aplicaciones basadas en criptografía de curvas elípticas y pruebas de conocimiento cero.  
    * Diseñada para ser eficiente en circuitos ZKP, reduciendo las restricciones en las pruebas.  
    * Compatible con el estándar `no_std`, permitiendo su uso en sistemas embebidos y entornos de recursos limitados.  
    * Fácil integración en proyectos criptográficos que requieren hashing seguro y eficiente.  
    * Mantenido activamente por el equipo de Dusk Network, con un enfoque en aplicaciones de privacidad y escalabilidad.  
 * 🌐 **Recursos:**
    - [Repositorio GitHub](https://github.com/dusk-network/poseidon252)
 * **Poseidon2**  
   * 📚 **Descripción:** **Poseidon2** es una implementación optimizada de la función hash Poseidon desarrollada por **Horizen Labs** en Rust. Poseidon es un algoritmo hash criptográfico diseñado específicamente para aplicaciones en pruebas de conocimiento cero (zk-SNARKs y zk-STARKs), ofreciendo una construcción eficiente en términos de restricciones en circuitos zk.  
   * 🔧 **Características principales:**  
     * Implementación del algoritmo Poseidon hash optimizado para su uso en circuitos zk.  
     * Enfocado en mejorar el rendimiento y reducir el número de restricciones en pruebas de conocimiento cero.  
     * Compatible con el estándar `no_std`, lo que permite su integración en dispositivos con recursos limitados.  
     * Ideal para aplicaciones de privacidad y seguridad, como contratos inteligentes, identificaciones digitales y sistemas descentralizados.  
     * Mantenido activamente por Horizen Labs, con un enfoque en aplicaciones avanzadas de criptografía.  
   * 🌐 **Recursos:**
     - [Repositorio GitHub](https://github.com/HorizenLabs/poseidon2)

* **Poseidon**  
  * 📚 **Descripción:**  
    **Poseidon** es una implementación en Rust de la función hash Poseidon, diseñada por el equipo de **Privacy & Scaling Explorations**. Este algoritmo hash está optimizado para su uso en pruebas de conocimiento cero (zk-SNARKs y zk-STARKs) y aplicaciones que requieren eficiencia y seguridad criptográfica en entornos avanzados.  
  * 🔧 **Características principales:**  
    * Implementación de Poseidon con soporte para configuraciones altamente personalizables según el campo y el circuito zk.  
    * Optimizaciones específicas para reducir las restricciones en circuitos zk, lo que mejora el rendimiento de las pruebas.  
    * Diseñado para integrarse fácilmente con proyectos de criptografía avanzada y escalabilidad.  
    * Compatible con el estándar `no_std`, permitiendo su uso en entornos embebidos o de recursos limitados.  
    * Mantenido activamente por el equipo de Privacy & Scaling Explorations, enfocado en tecnologías de escalabilidad y privacidad.  
   * 🌐 **Recursos:**
    - [Repositorio GitHub](https://github.com/privacy-scaling-explorations/poseidon)
### Password-Hashing-Functions
* **RustCrypto/password-hashes**  
  * 📚 **Descripción:**  
    **RustCrypto/password-hashes** es un conjunto de implementaciones de funciones de derivación de contraseñas (Password Hashing Functions, PHFs) en Rust. Este repositorio proporciona soluciones seguras y eficientes para proteger contraseñas en aplicaciones y sistemas que requieren almacenamiento y validación de contraseñas de forma robusta.  
  * 🔧 **Características principales:**  
    * Implementaciones de funciones de hashing de contraseñas como Argon2, bcrypt y PBKDF2.
    * Funciones optimizadas para ser seguras y resistentes a ataques de fuerza bruta, utilizando factores de coste ajustables para incrementar la seguridad.
    * Compatible con el estándar `no_std`, lo que permite su uso en sistemas embebidos.
    * Integración sencilla en proyectos de Rust, con un enfoque en la simplicidad y seguridad.
    * Mantenido por la comunidad de RustCrypto, con un enfoque en ofrecer soluciones seguras y eficientes para el manejo de contraseñas.
  * 🌐 **Recursos:**
    - [Repositorio GitHub](https://github.com/RustCrypto/password-hashes/tree/master)

* **rust-bcrypt**  
  * 📚 **Descripción:**  
    **rust-bcrypt** es una implementación de bcrypt en Rust, un algoritmo de hashing de contraseñas resistente a ataques de fuerza bruta. bcrypt es ampliamente utilizado para proteger contraseñas almacenadas, utilizando un factor de costo ajustable que aumenta el tiempo de cálculo y, por ende, la seguridad.  
  * 🔧 **Características principales:**  
    * Implementación de bcrypt con soporte para el ajuste del factor de costo (cost factor), lo que permite aumentar la seguridad contra ataques de diccionario y de fuerza bruta.
    * Utiliza una sal aleatoria para cada contraseña, lo que asegura que las contraseñas idénticas tengan hashes diferentes.
    * Interfaz sencilla y segura para la creación, verificación y comparación de hashes de contraseñas.
    * Compatible con el estándar `no_std`, permitiendo su uso en entornos de recursos limitados o dispositivos embebidos.
    * Mantenido activamente, con actualizaciones periódicas para garantizar su seguridad y eficiencia.
  * 🌐 **Recursos:**
    - [Repositorio GitHub](https://github.com/Keats/rust-bcrypt)

* **phpass**  
  * 📚 **Descripción:**  
    **phpass** es una implementación de bcrypt y hashing de contraseñas en PHP, diseñada para ser ligera y eficiente. Utiliza el algoritmo de hashing bcrypt con una sal aleatoria para proteger las contraseñas almacenadas en sistemas PHP. Este enfoque proporciona una capa adicional de seguridad al hacer que sea mucho más difícil realizar ataques de diccionario o fuerza bruta.  
  * 🔧 **Características principales:**  
    * Implementación del algoritmo bcrypt para el hashing de contraseñas.
    * Soporte para la creación y verificación de contraseñas con una sal aleatoria, lo que asegura que las contraseñas idénticas tengan hashes distintos.
    * El factor de costo (cost factor) es configurable, lo que permite ajustar la seguridad contra ataques de fuerza bruta según la potencia computacional disponible.
    * Mantenido activamente con mejoras periódicas para garantizar su seguridad y eficiencia.
    * Compatible con aplicaciones PHP de cualquier tamaño, desde sitios web pequeños hasta aplicaciones de gran escala.
  * 🌐 **Recursos:**
    - [Repositorio GitHub](https://github.com/clausehound/phpass)
* **RustCrypto/formats/pkcs5**  
  * 📚 **Descripción:**  
    **RustCrypto/formats/pkcs5** es una implementación de los estándares de formato PKCS #5 para el manejo de contraseñas en Rust. PKCS #5 define un formato para la derivación de claves de contraseñas, que es fundamental para la seguridad en la criptografía de contraseñas. Este repositorio proporciona una implementación eficiente y segura de estos formatos, incluyendo la derivación de claves utilizando funciones como PBKDF2.  
  * 🔧 **Características principales:**  
    * Implementación de PBKDF2, un algoritmo de derivación de claves basado en contraseñas que utiliza un enfoque de función de repetición para proteger las contraseñas contra ataques de diccionario.
    * Compatible con el estándar `no_std`, permitiendo su uso en sistemas embebidos o entornos con recursos limitados.
    * Proporciona una interfaz sencilla y segura para la derivación de claves a partir de contraseñas en aplicaciones Rust.
    * Mantenido activamente por la comunidad de RustCrypto, con un enfoque en la seguridad y eficiencia de las funciones criptográficas.
  * 🌐 **Recursos:**
    - [Repositorio GitHub](https://github.com/RustCrypto/formats/tree/master/pkcs5)
   
 * **rust-argon2**  
   * 📚 **Descripción:**  **rust-argon2** es una implementación de la función de derivación de claves Argon2 en Rust. Argon2 es un algoritmo de hashing de contraseñas resistente a ataques de fuerza bruta y diseñado para ser seguro en un entorno con recursos limitados. Esta implementación está diseñada para ser eficiente, flexible y fácil de usar, permitiendo ajustar el tiempo de cálculo y el uso de memoria para aumentar la seguridad.  
   * 🔧 **Características principales:**  
     * Implementación del algoritmo de derivación de claves Argon2 con soporte para los tres modos de operación: Argon2d, Argon2i y Argon2id.
     * Permite ajustar el número de iteraciones, el tamaño de memoria y el paralelismo para optimizar el uso de recursos y aumentar la seguridad.
     * Función de "sal" aleatoria para asegurar que los hashes de contraseñas idénticas sean diferentes.
     * Compatible con el estándar `no_std`, lo que permite su uso en entornos embebidos y con recursos limitados.
     * Mantenido activamente por la comunidad de Rust, con un enfoque en la seguridad y la flexibilidad.
   * 🌐 **Recursos:**
     - [Repositorio GitHub](https://github.com/sru-systems/rust-argon2)

