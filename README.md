# 🟦🟥 Cuadriláteros - Juego de Estrategia en Smalltalk

> Trabajo Práctico Integrador para la materia **Paradigmas de Programación**.
> Desarrollado enteramente en **Pharo 7** utilizando el paradigma Orientado a Objetos.

## 📖 Descripción
**Cuadriláteros** es un juego de estrategia territorial por turnos donde el objetivo es conquistar la mayor cantidad de área en una grilla limitada.

Los jugadores lanzan dados para definir las dimensiones de sus figuras y deben ubicarlas estratégicamente en el tablero, bloqueando al oponente y optimizando el espacio disponible. El juego termina cuando no es posible colocar más figuras.

## ✨ Características Principales
* **Modo Versus:** Multijugador local (1vs1).
* **Inteligencia Artificial (CPU):**
    * Implementación de un agente autónomo que busca espacios vacíos.
    * Uso de **heurísticas** para maximizar puntaje (ej: uso estratégico del comodín).
* **Reglas Especiales:**
    * 🎲 **Comodín (1):** Permite al jugador elegir el valor del dado.
    * ✨ **Bonus de Cuadrado:** Turno extra si la figura es un cuadrado perfecto.
* **Interfaz Gráfica (GUI):**
    * Desarrollada con **Morphic** (Framework nativo de Pharo).
    * Sistema de colores dinámico y carga de assets externos.

## 🛠️ Tecnologías y Diseño
Este proyecto fue construido siguiendo estrictamente los principios de la Programación Orientada a Objetos (POO):

* **Lenguaje:** Smalltalk (Entorno Pharo 7.0).
* **Arquitectura:** MVC (Modelo-Vista-Controlador) para desacoplar la lógica del juego de la interfaz Morphic.
* **Polimorfismo:** Utilizado para tratar indistintamente a jugadores Humanos y CPU.
* **Estructuras de Datos:** Uso eficiente de `Array` (matriz), `OrderedCollection` (historial) y `Dictionary` (configuraciones).
* **Dependencias:** Cero librerías externas. Todo construido sobre el núcleo estándar de Pharo.

## 🚀 Instalación y Ejecución

41.  Ejecuta el archivo:
    * **Windows:** Doble clic en `Jugar.bat`.
    * **Linux/Mac:** Ejecuta la imagen con tu VM de Pharo local.


## 👥 Autores
* **Di Rado Luciano** - *Desarrollo y Lógica* 
* **Gonzales Alessandro** - *Interfaz, Desarrollo y Lógica*
* **Kowtun Andrea** - *Interfaz, Diseño, Desarrollo, Testing y Documentación* [https://www.linkedin.com/in/andrea-kowtun-desarrolladora-backend/]
* **Pozzer Mauricio** - *Documentación*

---
*Proyecto realizado para la Universidad Tecnologica Nacional Facultad Regional Resistencia (UTN-FRRE) - 2025.*
