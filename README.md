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

Al desarrollar una pagina web el mostrar mucha información (imágenes, títulos y descripciones) puede saturar la pantalla. Este componente resuelve el problema del espacio proporcionando una interfaz limpia y navegable. Esta libreria es reutilizable por lo que evita que el desarrollador tenga que escribir código "hardcodeado" o depender de librerías externas o frameworks como React o Vue. Un ejemplo de uso de esta libreria podria ser en páginas de turismo donde quieres presentar varios lugares turisticos sin saturar la pantalla.

---

## Instalación
Para hacer uso de esta libreria en tu proyecto, solo debes descargar e incluir el archivo .js y .css en tu documento HTML.

1. Vincula el archivo CSS dentro de la etiqueta `<head>`:
```html
<link rel="stylesheet" href="css/componente.css">
```

2. Vincula el archivo JavaScript justo antes de cerrar la etiqueta `</body>`:
```html
<script src="js/componente.js"></script>
```

---

## Uso del Componente
La librería está diseñada para ser fácil de implementar. A continuación se muestra cómo inicializar un carrusel paso a paso.

### 1. Preparar el contenedor HTML
Crea un `<div>` vacío con un `id` único donde deseas que se renderice el carrusel:

```html
<div id="mi-carrusel"></div>
```

### 2. Inicializar con JavaScript
En el archivo principal de scripts o en una etiqueta `<script>` deberas crear un arreglo de objetos con tu información dinámica y pásalo al constructor de la clase `Carrusel` como se muestra a continuación:

```javascript
const misDatos = [
    { 
        img: 'img/rico.jpg', titulo: 'Rico', descripcion: 'Dispara balas que rebotan en los muros.' 
    },
    { 
        img: 'img/shelly.jpg', titulo: 'Shelly', descripcion: 'Ideal para combate a corta distancia.' 
    }
];
```
### 3. Instanciar el componente 
Deberas pasar el id del contenedor y los datos para que la libreria cumpla su funcion de carrusel dinamico.
```javascript
const carruselDemo = new Carrusel('mi-carrusel', misDatos);
```

---

## Capturas de pantalla( Evidencia)

*Aquí se muestra el componente renderizado y funcionando en el navegador:*

![Captura del carrusel funcionando](ruta/a/tu/pri_pag.png)

*Cambio de imagen en el carrusel probando el uso de los botones:*

![Captura de la consola/DOM](ruta/a/tu/seg_pag.png)

---

## Video promocional
Haz clic en el enlace de abajo para ver el componente en acción y conocer cómo implementarlo en menos de 60 segundos.

[Video promocional](enlace-a-tu-video-de-youtube-o-drive)
