# cartSync

Este proyecto consiste en una aplicación desarrollada con Ionic y Angular orientada a la gestión colaborativa de listas de compra. Su objetivo es permitir que varios usuarios puedan organizar y gestionar productos dentro de listas compartidas, facilitando la coordinación entre miembros de un mismo grupo.

La aplicación permite crear grupos de usuarios, dentro de los cuales se pueden generar distintas listas de compra. En cada lista es posible añadir productos con información relevante como el nombre, la categoría, la tienda habitual o una imagen del producto. Los miembros del grupo pueden interactuar con la lista marcando productos como comprados o pendientes, manteniendo la información sincronizada entre todos los participantes.

Para la gestión de datos y autenticación se utiliza Firebase, aprovechando sus servicios serverless para manejar el registro de usuarios, la persistencia de información y el almacenamiento de imágenes. Gracias al uso de Cloud Firestore, los cambios realizados en las listas se reflejan en tiempo real para todos los usuarios conectados.

El proyecto está planteado con una arquitectura modular basada en funcionalidades, separando las distintas responsabilidades de la aplicación para facilitar su mantenimiento y escalabilidad. Además, está preparado para ejecutarse como Progressive Web App (PWA), permitiendo su uso tanto en dispositivos móviles como en navegadores.
