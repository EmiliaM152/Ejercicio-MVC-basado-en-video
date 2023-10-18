# Ejercicio-MVC-basado-en-video

Diagrama de la  Aplicación del diseño de ingeniería

![image](https://github.com/EmiliaM152/Ejercicio-MVC-basado-en-video/assets/115099264/04d8c766-4377-4258-8311-86a83543ea35)

#Cliente Web (Navegador):# Los usuarios interactúan con la aplicación a través de un navegador web. El cliente web representa la capa de presentación.
Capa de Presentación (Vista): Esta capa consiste en componentes de React que gestionan la interfaz de usuario y la interacción del usuario. 
Estos componentes renderizan la vista y responden a eventos del usuario.
Capa de Control (Controlador): Los controladores de React manejan la lógica de la aplicación, incluyendo la gestión de eventos, la navegación y 
la comunicación con la capa de servicios (.NET API).
Capa de Servicios (Modelo): Esta capa es una aplicación .NET que contiene la lógica de negocio y se comunica con la base de datos. 
Proporciona una API para que los controladores de React accedan a los datos y realicen operaciones relacionadas con la lógica de negocio.
Base de Datos: Almacena los datos de la aplicación. Puede ser una base de datos relacional o no relacional, dependiendo de los requisitos del proyecto

Este diseño de ingeniería sigue el patrón de arquitectura MVC para lograr una separación clara de las responsabilidades 
y facilitar el desarrollo escalable y mantenible de aplicaciones web. React se utiliza para la capa de presentación, 
mientras que .NET proporciona la lógica de negocio y los servicios. La comunicación entre estas capas se realiza a través
de solicitudes HTTP o una API.
