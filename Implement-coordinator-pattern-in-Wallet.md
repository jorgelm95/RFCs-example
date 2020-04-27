# Implememntation coordinator pattter on Wallet

Autores:
 - @jorgelm95

## 1 Explicacion de la propuesta de cambio

implementation of the coordinator in the wallet application to improve navigation between screens and the dependency injection systems of the application

## 2 Motivación
The main motivation to implement this pattern in the application is to be able to reduce the coupling in the navigation part of the app, kill the different dependency injection modules that are living all the time in the application
without many of them being used and being able to achieve greater scalability when creating new features

## 3 Propuesta de implementación


<!--
Este es el núcleo de tu propuesta, y su proposito es ayudarte a pensar en la solución. Esto debe ser un wireframe, no un documento perfecto con todos los detalles.


  - usa diagramas para ilustrat tus ideas o flujos
  - inluye ejemplos de código si estas proponiendo una interfaz o contrato de sistemsa nuevo
  - agrega links con las especificaciones de proyectos

El proposito de esta sección se resume en:
"Esta es la dirección en la que nos voy a llevar, alguién ve huecos en mi propuesta o tiene comentarios sobre cómo mejorarla?

 -->

## 4 Métricas (Opcional)
N/A

## 5 Riesgos e inconvenientes
- The team does not have all the knowledge to implement the pattern
- Not finding a correct way to coexist correctly with the current dependency modules and the new dependency injection system

## 6 Alternativas
- usar un router para manejar la navegacion
- usar una libreria para el manejo de inyección de dependencias.

## 7 Impacto potencial y dependencias
The modules that will be affected are

- Wallet HR
- Wallet Credentialing

## 8 Preguntas sin resolver
N/A

## 9 Conclusión

Implementing this pattern in the app will help us to have better scalability, better cohesion and management
of the flow of navigation and injection dependent on the application. 


