# 🔐 **Awesome Rust Cryptography**  

🌟 Una colección curada de herramientas, bibliotecas y recursos en Rust para trabajar con criptografía, Zero-Knowledge Proofs (ZKPs), y tecnologías relacionadas. ¡Explora el poder de Rust en el mundo de la seguridad y privacidad digital! 🚀  

## 📖 **¿Por qué Rust para Criptografía?**  
Rust ofrece seguridad, eficiencia y soporte para programación concurrente, convirtiéndolo en un lenguaje ideal para construir aplicaciones y herramientas criptográficas confiables y escalables. 💪  

Con estos recursos, puedes adentrarte en el emocionante mundo de la criptografía y las pruebas de conocimiento cero utilizando Rust. 🚀  

---

## 🛠️ **Librerías y Proyectos Destacados**
* [ZKPs](##Zero-Knowledge)
  * [IA-MKZL](###IA-ZKML)
  * [Recurso Educativo](###Recurso-Educativo)
  * [Librerías Avanzadas de ZKP](###Librerías-Avanzadas-ZKP)


## Zero-Knowledge
📖 **¿Qué son las Pruebas de Conocimiento Cero (ZKPs)?**

Las **pruebas de conocimiento cero** son un tipo de protocolo criptográfico que permite a una parte (el "prover") demostrar que posee cierta información sin revelar la información en sí misma. Las ZKPs son fundamentales para aplicaciones que requieren alta seguridad y privacidad, como la verificación de transacciones en blockchain sin comprometer la confidencialidad de los datos.

### IA-ZKML
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
