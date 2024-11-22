
<br>
<br>
<h1 align="center"> Universidad Tecnológica de Xicotepec de Juárez </h1>
<br>

<h2 align="center"> Desarrollo Móvil Integral </h2>
<h2 align="center"> DMI-10B-YesNoApp 210857 </h2>
<h2 align="center"> Por: Maximiliano Amador Peña </h2>
<br>
<h2> Objetivo </h2>
Realizar una aplicación en Flutter para Dispositivos Móviles, parte de la Unidad 2 de la asignatura de Desarrollo Móvil Integral, para comprender el usos de Stateless y Statefull Widgets.
<br>
<h2 align="center"> Documentación del proyecto </h2>




<br>
<h3> Practica 21 </h3>

| Codigo | Resultado | Descripción | 
|:-------------:|:---------------:|:------------------------------------------------------:|
| ![Captura de pantalla 2024-11-22 004039](https://github.com/user-attachments/assets/a278bdc1-bc0d-4830-a357-d0c581775cec) | ![WhatsApp Image 2024-11-22 at 12 38 54 AM](https://github.com/user-attachments/assets/24ca868b-95e9-4486-ac72-215eb93b12e8) | Para la práctica 21 se creó el widget `ChatScreen` que es la pantalla donde se muestra un chat. Tiene una barra de aplicaciones (AppBar) con un avatar de usuario y un título, y el cuerpo de la pantalla está destinado a mostrar la vista del chat con `_ChatView` como widget encargado de ello. Se inicializa la aplicación utilizando el widget `MyApp`, el cual configura la gestión del estado mediante `Provider`, aplica un tema personalizado definido en `AppTheme` y establece la pantalla principal (`ChatScreen`). Esta estructura permite gestionar el estado de manera centralizada y asegura que la interfaz de usuario esté basada en el diseño de Material Design, proporcionando una experiencia consistente y eficiente para el usuario. |

<h3> Practica 22 </h3>

| Codigo | Resultado | Descripción |
|:-------------:|:-------------:|:---------------------------------------------------------:|
| ![Captura de pantalla 2024-11-22 003937](https://github.com/user-attachments/assets/785fa620-fe6a-48c8-bae7-69d3c33b35ff) | ![WhatsApp Image 2024-11-22 at 12 38 54 AM(1)](https://github.com/user-attachments/assets/d73e4771-a341-4345-8d95-aafc021ff4c4) | El widget realizado `MyMessageBubble` es un componente de interfaz de usuario que forma una burbuja de mensaje enviada por el usuario en la aplicación. Se diseñó para mostrar texto estilizado en un contenedor con bordes redondeados, utilizando los colores definidos en el tema de la aplicación. La clase `ChatProvider` es un `ChangeNotifier` que administra el estado del chat para así controlar el desplazamiento automático de la vista del chat. |

<h3> Practica 23 </h3>

| Codigo | Resultado | Descripción |
|:-------------:|:-------------:|:----------------------------------------------------------:|
| ![Captura de pantalla 2024-11-22 003418](https://github.com/user-attachments/assets/872fc18c-3e2e-4e59-abf5-5c3e58b495ee) | ![WhatsApp Image 2024-11-22 at 12 38 54 AM(2)](https://github.com/user-attachments/assets/2038b168-b81d-4b8a-a452-63ed5d5a0006) | Se creó la clase `YesNoModel` para que represente la estructura de una respuesta en un sistema que devuelve "Sí" o "No". Después se creó `GetYesNoAnswer`, que es responsable de realizar una solicitud HTTP para obtener una respuesta de tipo "Sí" o "No" y convertir esta respuesta en un objeto de tipo `Message`. Utilizando la biblioteca Dio para la comunicación HTTP y el modelo `YesNoModel` para gestionar la respuesta. |

