# Patron Observador :rocket:

Observer es un patrón de diseño de comportamiento que te permite definir un mecanismo de suscripción para notificar a varios objetos sobre cualquier evento que le suceda al objeto que están observando.

# Objetivo o intención del patrón

El objeto que tiene un estado interesante suele denominarse sujeto, pero, como también va a notificar a otros objetos los cambios en su estado, le llamaremos notificador (en ocasiones también llamado publicador). El resto de los objetos que quieren conocer los cambios en el estado del notificador, se denominan suscriptores.

El patrón Observer sugiere que añadas un mecanismo de suscripción a la clase notificadora para que los objetos individuales puedan suscribirse o cancelar su suscripción a un flujo de eventos que proviene de esa notificadora. ¡No temas! No es tan complicado como parece. En realidad, este mecanismo consiste en: 

1.  un campo matriz para almacenar una lista de referencias a objetos suscriptores y
2.  varios métodos públicos que permiten añadir suscriptores y eliminarlos de esa lista.

# Implementación

Si te suscribes a un periódico o una revista, ya no necesitarás ir a la tienda a comprobar si el siguiente número está disponible. En lugar de eso, el notificador envía nuevos números directamente a tu buzón justo después de la publicación, o incluso antes.

El notificador mantiene una lista de suscriptores y sabe qué revistas les interesan. Los suscriptores pueden abandonar la lista en cualquier momento si quieren que el notificador deje de enviarles nuevos números.

## Diagrama

![PatronObservador](https://github.com/Jhon599/PatronObservador/assets/143898470/6e622553-0ff6-4c47-ab1c-874d2dfef3d0)

## Tecnologia
- JAVA Maven
- Editor DIA
- IntelliJ IDEA
