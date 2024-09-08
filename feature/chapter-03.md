# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping

**Arrendatario (Compradores juveniles)**

![image](https://i.postimg.cc/WbwXynP3/Captura-de-pantalla-2024-09-01-011756.png)

**Arrendador (Propietarios de Inmuebles Independientes)**

![image](https://i.postimg.cc/wTwDJbph/Captura-de-pantalla-2024-09-01-012147.png)

## 3.2. User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|--------------------------|--------------------------|
| EPIC001 | Creación de la Landing Page | Como usuario quiero contar con un sitio web para poder guiarme y conocer más sobre la aplicación. | - | - |
| US001 | Página de Inicio | Como visitante deseo ser dirigido a la página inicial del sitio web de la aplicación para tener un acercamiento general sobre esta. | **Escenario 1: Acceso exitoso** **Dado que** el visitante desea ingresar al sitio web, Cuando selecciona el enlace, Y tiene acceso a internet, Entonces es dirigido a la sección de inicio. **Escenario 2: Acceso denegado** **Dado que** el visitante desea ingresar al sitio web, Cuando selecciona el enlace Y no tiene acceso a internet, Entonces el contenido de la sección inicial no es visible Y su navegador le informa que no está conectado a internet. | EPIC001 |
| US002 | Pestaña“Sobre” | Como visitante, quiero poder acceder a la pestaña "Sobre" para obtener más información sobre la aplicación. | **Escenario 1: Acceso exitoso** **Dado que** un visitante quiere conocer más sobre la organización Cuando el visitante hace click en la pestaña "Sobre". Y tiene acceso a internet Entonces es dirigido a la página con información sobre nosotros. **Escenario 2: Acceso denegado** **Dado que** un visitante quiere conocer más sobre la organización Cuando presiona la pestaña "Sobre". Y no tiene acceso a internet Entonces no puede visualizar el contenido de la página Y su navegador le informa que no está conectado a internet. | EPIC001 |
| US003 | Pestaña “Contacto” | Como visitante, quiero poder acceder a la pestaña “Contacto” para ponerme en contacto con el equipo de la aplicación. | **Escenario 1: Acceso exitoso** **Dado que** un visitante quiere enviar consultas, Cuando un visitante le da click en la pestaña "Contacto" Y cuenta con acceso a internet, Entonces debe ser dirigido a la página establecida para contacto Y ver un formulario que permite enviar consultas. **Escenario 2: Acceso denegado** **Dado que** un visitante quiere enviar consultas, Cuando un visitante le da click en la pestaña "Contacto", Y no dispone de acceso a internet, Entonces no  puede ver el contenido de la página de contacto Y su navegador le informa que no se pudo encontrar la dirección IP. | EPIC001 |
| US004 | Envío de correos | Como visitante, quiero estar siempre informado por eso quiero que me envíen correos para comprender más las funcionalidades de la aplicación. | **Escenario 1: Envío de correos tras una acción de registro de usuario** **Dado que** un visitante se registra en la aplicación. Cuando el registro es exitoso Entonces el sistema debe enviar un correo de bienvenida con información básica sobre las funcionalidades de la aplicación. **Escenario 2: Envío de correos tras una solicitud de información adicional** **Dado que** el visitante solicita información adicional Cuando la solicitud es procesada, Entonces el sistema debe enviar un correo Y sale un mensaje que dice “El correo fue enviado con éxito” | EPIC001 |
| US005 | Pestaña de ayuda al usuario | Como visitante, quiero contar con una sección de ayuda en el sitio web para poder resolver dudas frecuentes. | **Escenario 1: Acceso a preguntas frecuentes para resolver dudas** **Dado que** un visitante quiere resolver sus dudas. Cuando un visitante hace click en la pestaña "Centro de Ayuda". Entonces debe ser dirigido al centro de ayuda Y se debe proporcionar respuestas claras a preguntas frecuentes. **Escenario 2: Las preguntas frecuentes no resuelven todas las dudas** **Dado que** un visitante quiere resolver sus dudas. Cuando presiona la pestaña "Centro de Ayuda". Y no encuentra la respuesta a sus dudas Entonces recibe la recomendación de contactarnos a través de correo electrónico o teléfono celular. | EPIC001 |
| EPIC002 | Gestión de usuarios | Como administrador del sistema, quiero poder gestionar los perfiles de usuario para garantizar la integridad de los datos y la seguridad de la plataforma. | - | - |
| US006 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC002 |
| US007 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC002 |
| US008 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC002 |
| US009 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC002 |
| US010 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC002 |
| EPIC003 | Gestión de Propiedades | - | - | - |
| US011 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC003 |
| US012 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC003 |
| US013 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC003 |
| US014 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC003 |
| US015 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC003 |
| US016 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC003 |
| EPIC004 | Funcionalidades de búsqueda | Como usuario, quiero poder buscar propiedades según mis criterios para encontrar la opción que se ajuste a mis necesidades. | - | - |
| US017 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC004 |
| US018 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC004 |
| EPIC005 | Reserva de citas a propiedades | Como usuario interesado en una propiedad, quiero poder reservar una cita para ver la propiedad en persona, para facilitar la organización y planificación. | - | - |
| US019 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC005 |
| US020 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC005 |
| US021 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC005 |
| US022 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC005 |
| EPIC006 | Gestión legal | - | - | - |
| US023 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC006 |
| US024 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC006 |
| US025 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC006 |
| US026 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC006 |
| US027 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC006 |
| US028 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC006 |
| EPIC007 | Gestión de método de  pago | - | - | - |
| US029 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC007 |
| US030 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC007 |
| US031 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC007 |
| US032 |  |  | **Escenario 1: ** **Dado que** **Escenario 2: ** **Dado que** | EPIC007 |
## 3.3. Impact Mapping

![image](https://i.postimg.cc/ZRMcd6Tk/Impact-map-1-1.png)

## 3.4. Product Backlog

