# 🔐 **Awesome Rust Cryptography**  

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
