# Librería de Componente visual: Carrusel

### TECNOLÓGICO NACIONAL DE MÉXICO/
### INTITUTO TECNOLÓGICO DE OAXACA

#### Carrera: Ingeniería en Sistemas Computacionales
#### Estudiante: Macuixtle Gaytán Miguel Angel
#### Materia: Programación Web
#### Docente: Martinez Nieto Adelina
#### Unidad: 2
#### Actividad 2: Libreria Utileria .js
#### Fecha: 04/07/2026

## ¿Qué problema resuelve?

**Problema que resuelve:** En el desarrollo web moderno, mostrar mucha información (imágenes, títulos y descripciones) puede saturar la pantalla. Este componente resuelve el problema del espacio proporcionando una interfaz limpia y navegable. Al ser **100% dinámico y reutilizable**, evita que el desarrollador tenga que escribir código "hardcodeado" o depender de librerías externas o frameworks como React o Vue. Permite instanciar múltiples carruseles en una misma página de forma completamente independiente.

---

## Instalación
Para utilizar este componente en tu proyecto, solo debes incluir los archivos de estilo y lógica en tu documento HTML.

1. Vincula el archivo CSS dentro de la etiqueta `<head>`:
```html
<link rel="stylesheet" href="css/componente.css">
```

2. Vincula el archivo JavaScript justo antes de cerrar la etiqueta `</body>`:
```html
<script src="js/componente.js"></script>
```

---

## 💻 Uso del Componente
La librería está diseñada para ser fácil de implementar. A continuación se muestra cómo inicializar un carrusel paso a paso.

### 1. Preparar el contenedor HTML
Crea un `<div>` vacío con un `id` único donde deseas que se renderice el carrusel:

```html
<div id="mi-carrusel"></div>
```

### 2. Inicializar con JavaScript
En tu archivo principal de scripts o en una etiqueta `<script>`, crea un arreglo de objetos con tu información dinámica y pásalo al constructor de la clase `Carrusel`:

```javascript
// 1. Definir los datos (contenido dinámico)
const misDatos = [
    { 
        img: 'img/rico.jpg', 
        titulo: 'Rico', 
        descripcion: 'Dispara balas que rebotan en los muros.' 
    },
    { 
        img: 'img/shelly.jpg', 
        titulo: 'Shelly', 
        descripcion: 'Ideal para combate a corta distancia.' 
    }
];

// 2. Instanciar el componente pasando el ID del contenedor y los datos
const carruselDemo = new Carrusel('mi-carrusel', misDatos);
```

---

## 📸 Capturas de Pantalla

*Aquí se muestra el componente renderizado y funcionando en el navegador:*

![Captura del carrusel funcionando](ruta/a/tu/captura-carrusel.png)

*Estructura generada dinámicamente en el DOM (Pestaña Elements del navegador):*

![Captura de la consola/DOM](ruta/a/tu/captura-consola.png)

---

## 🎥 Video Demostrativo
Haz clic en el enlace de abajo para ver el componente en acción y conocer cómo implementarlo en menos de 60 segundos.

[👉 VER VIDEO DEMOSTRATIVO AQUÍ 👈](enlace-a-tu-video-de-youtube-o-drive)
