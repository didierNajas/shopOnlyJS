# ShopOnlyJS

Sistema backend completo desarrollado en **JavaScript** utilizando **Programación Orientada a Objetos (POO)**. Este proyecto gestiona usuarios, productos y órdenes con una arquitectura modular, escalable y limpia, implementando los principios fundamentales de herencia, encapsulamiento y polimorfismo.

## Descripción

Este repositorio contiene la lógica de negocio para un sistema de comercio electrónico (backend). El código está estructurado en módulos independientes que interactúan entre sí mediante clases y objetos, facilitando el mantenimiento y la expansión del sistema.

### Características Principales
- **Arquitectura Modular:** Separación de responsabilidades en archivos distintos.
- **POO Avanzada:** Uso completo de herencia, encapsulamiento, abstracción y polimorfismo.
- **Gestión de Entidades:**
  - **Usuarios:** Registro, autenticación y gestión de perfiles.
  - **Productos:** Inventario, categorías y precios.
  - **Órdenes:** Procesamiento de compras y estados de transacción.
- **Estructuras de Datos:** Implementación eficiente para el manejo de colecciones de datos.

## Tecnologías

- **Lenguaje:** JavaScript (ES6+)
- **Entorno:** Node.js
- **Paradigma:** Programación Orientada a Objetos (POO)
- **Gestión de Datos:** Estructuras de datos nativas y personalizadas

## Estructura del Proyecto

El código se organiza en archivos específicos para cada dominio, promoviendo la reutilización y claridad:

```text
shopOnlyJS/
├── index.js          # Punto de entrada y orquestación del sistema
├── usuario.js        # Clases relacionadas con la gestión de usuarios
├── producto.js       # Clases relacionadas con el catálogo de productos
├── usuario.js        # Lógica específica de órdenes y transacciones
└── utilidades.js     # Funciones auxiliares y validaciones compartidas
