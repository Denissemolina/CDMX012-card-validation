# Tarjeta de crédito válida

## Índice

**1. Preámbulo**
**2. Prototipo**
**3. Objetivos de aprendizaje**
**4. Proyecto**
***

## 1. Preámbulo

El [algoritmo de Luhn](https://es.wikipedia.org/wiki/Algoritmo_de_Luhn),
también llamado algoritmo de módulo 10, es un método de suma de verificación,
se utiliza para validar números de identificación; tales como el IMEI de los
celulares, tarjetas de crédito, etc.

Este algoritmo es simple. Obtenemos la reversa del número a verificar (que
solamente contiene dígitos [0-9]); a todos los números que ocupan una posición
par se les debe multiplicar por dos, si este número es mayor o igual a 10,
debemos sumar los dígitos del resultado; el número a verificar será válido si
la suma de sus dígitos finales es un múltiplo de 10.

![gráfica de algoritmo de Luhn](https://www.101computing.net/wp/wp-content/uploads/Luhn-Algorithm.png)

## 2. Prototipo

En este proyecto se realizó un moodboard en Figma para buscar el estilo final de la aplicación de validador de tarjetas.
![gráfica de algoritmo de Luhn](./src/assets/moodboard-card.JPG)

## 3. Objetivos de aprendizaje

Los objetivos de aprendizaje reforzados en este proyecto fueron los siguientes:

### HTML
- :ringed_planet: **Uso de HTML semántico**

### CSS
- :rainbow: **Uso de selectores de CSS**
- :rainbow: **Modelo de caja (box model): borde, margen, padding**

### JavaScript
- :star2: **Uso de selectores del DOM**
- :star2: **Manejo de eventos del DOM (listeners, propagación, delegación)**
- :star2: **Manipulación dinámica del DOM**
- :star2: **Tipos de datos primitivos**
- :star2: **Strings (cadenas de caracteres)**
- :star2: **Variables (declaración, asignación, ámbito)**
- :star2: **Uso de condicionales (if-else, switch, operador ternario, lógica booleana)**
- :star2: **Uso de bucles/ciclos (while, for, for..of)**
- :star2: **Funciones (params, args, return)**
- :star2: **Pruebas unitarias (unit tests)**
- :star2: **Módulos de ECMAScript (ES Modules)**

### Control de Versiones (Git y GitHub)
- :octocat: **Git: Instalación y configuración**
- :octocat: **Git: Control de versiones con git (init, clone, add, commit, status, push, pull, remote)**
- :octocat: **GitHub: Creación de cuenta y repos, configuración de llaves SSH**
- :octocat: **GitHub: Despliegue con GitHub Pages**

### UX (User eXperience)
- :rocket: **Diseñar la aplicación pensando en y entendiendo al usuario**
- :rocket: **Crear prototipos para obtener feedback e iterar**
- :rocket: **Aplicar los principios de diseño visual**

### Interfaz de usuario (UI)
La interfaz permite al usuario:
- :woman_technologist: Insertar el número que queremos validar.
- :woman_technologist: Ver el resultado si es válido o no.
- :woman_technologist: Ocultar todos los dígitos de su número de tarjeta menos los últimos 4 caracteres.

## 4. Proyecto

![proyecto final](./src/assets/prototipo-card.JPG)
