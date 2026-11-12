# Calculadora Científica Zárate

Proyecto de Android Studio desarrollado con **Kotlin y Java**.

## Características
- Operaciones básicas, paréntesis y jerarquía de operaciones.
- Seno, coseno, tangente, grados y radianes.
- Potencias, raíces, porcentajes y π.
- Gráficas matemáticas e historial.
- Herramienta de propinas e impuestos.
- Modo claro/oscuro, sonido de botones y fondo parallax.
- Menú organizado para las herramientas.

**Nota:** La versión actual no incluye DOOM.

## Cómo ejecutar
1. Descarga el código del repositorio.
2. Abre Android Studio y selecciona **Open**.
3. Selecciona la carpeta que contiene `settings.gradle.kts`.
4. Sincroniza Gradle, selecciona un emulador o dispositivo y pulsa **Run**.

Configuración del proyecto: Android API mínima 24, compilación configurada para API 37.

## Archivos principales
- `app/src/main/java/com/example/zarate/MainActivity.kt` — interfaz y funciones.
- `app/src/main/java/com/example/zarate/ExpressionCalculator.java` — motor de cálculo.
- `app/src/main/java/com/example/zarate/GraphActivity.kt` — pantalla de gráficas.
- `app/src/main/assets/graph/` — gráficas HTML/JavaScript.
- `app/src/main/res/` — diseños, iconos, temas y sonido.

> El proyecto todavía requiere una compilación completa en Android Studio para confirmar su ejecución en el dispositivo.