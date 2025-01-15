# Ejercicio: CSS Intermedio - Diseño de una Tarjeta de Perfil

## Objetivo
Practicar el uso de propiedades avanzadas de CSS, incluyendo flexbox, pseudo-clases, y personalización de estilos para crear un diseño atractivo de una tarjeta de perfil.

## Descripción del Ejercicio

Vas a diseñar una tarjeta de perfil que contenga una imagen, un nombre, una breve descripción, y botones de acción. Se utilizarán propiedades como `flexbox` y estilos de bordes.

## Requisitos de Estilo
Crea un archivo llamado styles.css y cumple con los siguientes requisitos:

### Estructura básica

Centra la tarjeta en la pantalla usando flexbox.
Aplica un ancho máximo de 300px a la tarjeta y agrega un relleno (padding) de 20px.

### Estilo de la tarjeta

Aplica un color de fondo suave (por ejemplo, #f9f9f9).
Agrega un borde redondeado de 10px.
Usa una sombra para dar profundidad a la tarjeta.

### Estilo de la imagen

Haz que la imagen tenga forma circular.
Establece un tamaño fijo de 100px x 100px.
Estilo del texto:

Cambia la fuente del nombre a una fuente sans-serif y hazlo de color azul.
Aplica un color gris al texto de la descripción.

### Botones

Los botones deben tener bordes redondeados, sin borde visible.
Cambia el color de fondo del botón "Seguir" a verde y el de "Mensaje" a azul.
Al pasar el mouse sobre los botones cambia ligeramente el color de fondo.

## Archivo HTML

Copia el siguiente código en un archivo llamado `index.html`:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tarjeta de Perfil</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div>
    <img src="https://via.placeholder.com/150" alt="Foto de Perfil" />
    <h2>Juan Pérez</h2>
    <p>Desarrollador web enfocado en crear experiencias digitales únicas.</p>
    <div>
      <button>Seguir</button>
      <button>Mensaje</button>
    </div>
  </div>
</body>
</html>
