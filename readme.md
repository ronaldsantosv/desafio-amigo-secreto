# Challenge Amigo Secreto

Este proyecto es una aplicación web sencilla que permite a los usuarios ingresar nombres de amigos en una lista para luego realizar un sorteo aleatorio y determinar quién es el "amigo secreto".

## Características

- Permite agregar nombres a una lista.
- Valida que los nombres ingresados no estén vacíos ni duplicados.
- Muestra en pantalla la lista de nombres ingresados.
- Permite eliminar nombres de la lista.
- Realiza un sorteo aleatorio para seleccionar un "amigo secreto".
- Muestra el resultado en pantalla.

## Tecnologías utilizadas

- **HTML5** para la estructura de la página.
- **CSS3** para los estilos.
- **JavaScript** para la funcionalidad.

## Estructura del proyecto

```
📁 AmigoSecreto
│── 📄 index.html       # Estructura principal de la aplicación
│── 📄 style.css        # Estilos de la aplicación
│── 📄 app.js           # Lógica de la aplicación
│── 📁 assets          # Imágenes y recursos
│── 📄 README.md        # Descripción del proyecto
```

## Cómo usar la aplicación

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador.
3. Escribe un nombre en el campo de entrada y presiona "Añadir".
4. Verás los nombres en la lista. Puedes eliminarlos con el botón "X".
5. Presiona "Sortear Amigo" para obtener un amigo secreto al azar.

## Funcionalidades detalladas

### Agregar nombres

Los usuarios pueden escribir un nombre y presionar el botón "Añadir". Si el campo está vacío o el nombre ya existe en la lista, se mostrará una alerta.

### Visualizar la lista

Los nombres agregados se muestran en una lista debajo del campo de entrada.

### Eliminar nombres

Cada nombre tiene un botón "X" que permite eliminarlo de la lista.

### Sorteo aleatorio

El botón "Sortear Amigo" elige un nombre aleatorio de la lista y lo muestra en pantalla. Si no hay nombres en la lista, se muestra una alerta.

## Créditos

Desarrollado por Ronald Santos

---


