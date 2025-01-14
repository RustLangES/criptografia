# 🔐 **Criptografía aplicable con Rust**  

🌟 Una colección curada de herramientas, bibliotecas y recursos en Rust para trabajar con criptografía. ¡Explora el poder de Rust en el mundo de la seguridad y privacidad digital! 🚀  

## 📖 **¿Por qué Rust para Criptografía?**  
Rust ofrece seguridad, eficiencia y soporte para programación concurrente, convirtiéndolo en un lenguaje ideal para construir aplicaciones y herramientas criptográficas confiables y escalables. 💪  

Con estos recursos, puedes adentrarte en el emocionante mundo de la criptografía y las pruebas de conocimiento cero utilizando Rust. 🚀  

---

## 🛠️ **Librerías y Proyectos Destacados**
* [ZKPs](##Zero-Knowledge)
  * [IA-ZKML](###IA-ZKML-ZKVM)
  * [Recurso Educativo](###Recurso-Educativo)
  * [Librerías Avanzadas de ZKP](###Librerías-Avanzadas-ZKP)
  * [ZKTLS](###ZKTLS)
* [MPC](##Secure-Multiparty-Computation)
  * [Librerias de MPC](###Librerias-de-MPC)
  * [Frameworks de MPC](##Frameworks-de-MPC)
* [FHE](##Fully-Homomorphic-Encryption)
  * [Librerias de FHE](###Librerias-de-FHE)
 
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
 
## ZKTLS

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
    
    - [Repositorio GitHub](https://github.com/gausslabs/phantom-zone)
