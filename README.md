# Orientación a Objetos 2

Este repositorio contiene la resolución de las guías de trabajos prácticos de la materia **Orientación a Objetos 2**. El proyecto está estructurado siguiendo el orden cronológico de la cursada, dividido en módulos temáticos.

## 📂 Estructura del Repositorio

El repositorio se organiza en 4 directorios principales, cada uno correspondiente a una unidad temática. Dentro de cada directorio existe un `README` específico y subcarpetas para cada ejercicio.


### 1. [Repaso](./01-repaso)

Ejercicios introductorios para nivelar conceptos de Orientación a Objetos 1, tales como herencia, polimorfismo, encapsulamiento, heurísticas para la asignación de responsabilidades y principios SOLID.


### 2. [Patrones de Diseño](./02-patrones)

Implementación de patrones de diseño clásicos (GoF) aplicados a problemas concretos.


### 3. [Refactoring](./03-refactoring)

Ejercicios enfocados en la detección de *Code Smells* y la aplicación de técnicas de refactoring para mejorar la calidad del código sin alterar su comportamiento.


### 4. [Frameworks](./04-frameworks)

Desarrollo y utilización de frameworks, inversión de control e inyección de dependencias.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java 11
* **Gestor de Dependencias:** Maven
* **Testing:** JUnit 5


## 🚀 Cómo ejecutar los proyectos

Cada ejercicio es un proyecto Maven independiente.

1.  Clonar el repositorio:
    ```bash
    git clone [https://github.com/BrianBiscaro/orientacion-a-objetos-2.git](https://github.com/BrianBiscaro/orientacion-a-objetos-2.git)
    ```
2.  Navegar a la carpeta del ejercicio deseado:
    ```bash
    cd 02-patrones/ejercicio-03-media-player
    ```
3.  Ejecutar los tests (para verificar la solución):
    ```bash
    mvn test
    ```

