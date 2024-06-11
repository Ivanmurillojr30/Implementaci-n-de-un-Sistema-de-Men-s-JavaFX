# Proyecto de Ejemplo de Barra de Menú en JavaFX

Este proyecto es un ejemplo simple de cómo crear y manejar una barra de menú en una aplicación JavaFX. A continuación, se presenta una descripción detallada del código para ayudarte a comprender su estructura y funcionalidad.

# ilustraciones de lo ejecutado
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/5390ed4a-f072-4bf4-8c61-5c8fa37c4423)

![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/fc03825d-2699-4904-9170-8d08e3f613c9)


# Estructura del Código
Clase Main
La clase Main extiende Application, la clase base para las aplicaciones JavaFX. Dentro de esta clase se definen los elementos de la interfaz de usuario y se configuran sus acciones.

Método start(Stage primaryStage)
Este es el método principal que se ejecuta cuando se inicia la aplicación. Dentro de este método, se configuran los menús, la barra de menú, y las acciones para cada elemento del menú.

# Creación de Menús y Elementos de Menú:
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/a6e356b0-d5a6-4730-8a71-42b314be7e78)

Se crean tres menús: "Archivo", "Editar" y "Ayuda". Cada menú contiene varios elementos de menú, que son opciones que el usuario puede seleccionar.

# Creación de la Barra de Menú:

![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/d89a22ce-e7fc-4b09-b6cb-a0101d252425)
Se crea una barra de menú (MenuBar) y se agregan los menús creados previamente.

# Configuración del Layout:
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/e0c29f45-d45a-46c0-90de-ee7f3bde2231)

# Definición de Acciones para los Elementos del Menú:
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/fd1ba44b-7f32-4c8a-ba8e-d52571efc821)

Se asignan acciones a cada elemento del menú. Por ejemplo, al seleccionar "Nuevo", se imprime un mensaje en la consola. La opción "Salir" cierra la aplicación, y la opción "Acerca de..." muestra una ventana con información.

# Mostrar la Ventana Principal:
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/762da98b-66e4-48d1-9915-125b86e2c29e)

Se crea una escena (Scene) con el layout principal y se configura la ventana principal (primaryStage) para mostrarla.

Método mostrarAcercaDe()
Este método muestra una ventana de alerta con información sobre la aplicación.
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/1bea2354-c1b7-4f9b-b60a-7db66d3d4acf)

# Método main(String[] args)
Este es el punto de entrada de la aplicación. Simplemente llama al método launch(args) para iniciar la aplicación JavaFX.
![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/624426fd-8dc9-425c-a90d-ab0220b4405e)

# Estilos
El archivo de estilos application.css se incluye en la escena para personalizar la apariencia de la aplicación. Asegúrate de tener este archivo en el mismo paquete que la clase Main.

![image](https://github.com/Ivanmurillojr30/Implementaci-n-de-un-Sistema-de-Men-s-JavaFX/assets/168851753/6914dfa9-2441-470a-9817-1977782cc4cb)

# Dependencias
Este proyecto utiliza JavaFX, por lo que asegúrate de tener las dependencias adecuadas configuradas en tu entorno de desarrollo.

# Ejecución
Para ejecutar la aplicación, simplemente ejecuta el método main en la clase Main. Aparecerá una ventana con una barra de menú que permite interactuar con diferentes opciones.

# Contribución
Si deseas contribuir a este proyecto, puedes hacer un fork del repositorio, realizar tus cambios y enviar un pull request. Cualquier mejora o corrección es bienvenida.


