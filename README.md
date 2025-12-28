# 🦀 Funciones en Rust: 10 Ejercicios Prácticos

Este repositorio contiene una colección de 10 ejercicios diseñados para practicar la definición y el uso de **funciones personalizadas** en el lenguaje de programación Rust. Los ejercicios cubren conceptos clave como parámetros, tipos de retorno, la convención de nomenclatura `snake_case`, y el manejo de tipos de datos fundamentales.



## 📋 Ejercicios Incluidos

Cada ejercicio está diseñado para ser implementado en una función separada dentro del archivo `main.rs`.

| # | Título del Ejercicio | Conceptos a Practicar |
| :---: | :--- | :--- |
| **1** | Función `saludar` | Funciones sin parámetros. |
| **2** | Suma de Enteros (`sumar`) | Parámetros (`i32`), tipo de retorno. |
| **3** | Cálculo de Área (`area_rectangulo`) | Tipos de punto flotante (`f64`). |
| **4** | Verificación de Edad (`es_mayor_edad`) | Retorno de `bool`, expresiones `if/else`. |
| **5** | Función con Referencia (`imprimir_mensaje`) | Uso de referencias (`&str`), *borrowing*. |
| **6** | Factorial (`factorial`) | *Loops* (`for`), mutabilidad (`let mut`). |
| **7** | Potencia Simple (`potencia_cuadrada`) | Multiplicación/Uso de métodos. |
| **8** | Función con *Tuple* de Retorno (`obtener_coordenadas`) | Retorno de tuplas. |
| **9** | Función con Condición Múltiple (`clasificar_numero`) | Uso de `if-else if-else`, retorno de `String`. |
| **10** | Conversor de Temperatura (`celsius_a_fahrenheit`) | Operaciones aritméticas con `f64` (Fórmula: $F = C \times \frac{9}{5} + 32$). |

## 🚀 Cómo Empezar

### Prerrequisitos

Necesitas tener **Rust** y **Cargo** instalados en tu sistema.

1.  **Instalar Rust:** Puedes hacerlo a través de [rustup](https://rustup.rs/).
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf [https://sh.rustup.rs](https://sh.rustup.rs) | sh
    ```

### Instalación y Ejecución

Sigue estos pasos para crear y ejecutar tu proyecto de Rust:

1.  **Crear el proyecto:**
    ```bash
    cargo new funciones_practica
    cd funciones_practica
    ```

2.  **Escribir el código:**
    Reemplaza el contenido del archivo `src/main.rs` con tus implementaciones de las 10 funciones. Asegúrate de llamar a cada función desde la función `main()` para probar su salida.

    **Estructura sugerida para `src/main.rs`:**

    ```rust
    // 1. Función saludar
    fn saludar() {
        // ... implementación
    }

    // 2. Función sumar
    fn sumar(a: i32, b: i32) -> i32 {
        // ... implementación
    }

    // ... y así sucesivamente para las 10 funciones

    fn main() {
        // Aquí debes llamar a tus funciones para ver los resultados
        saludar();
        let resultado_suma = sumar(5, 7);
        println!("Suma: {}", resultado_suma);
        // ... llamadas de prueba para el resto de las funciones
    }
    ```

3.  **Ejecutar el programa:**
    ```bash
    cargo run
    ```
    Esto compilará y ejecutará tu código, mostrando los resultados en la terminal.

## 🤝 Contribución

¡Las sugerencias y mejoras son bienvenidas! Si tienes una implementación alternativa o un ejercicio de función interesante que añadir, no dudes en abrir un *Issue* o enviar un *Pull Request*.
