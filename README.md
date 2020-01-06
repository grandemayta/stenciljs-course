# Que es Stencil?
Stencil es un tool para generar Web Components. Esto significa que no estamos hablando de un framework como Angular o de una libreria como Vue, simplemente es un compilador.

## Que son Web Components?
Los Web Components son una tecnologia disponible en la mayor parte de navegadores modernos que nos permiten crear o extender elementos html independientes, reutilizables y encapsulables.

## Por que es necesario?
Stencil es util porque nos permite utilizar las APIs que sirven para crear Web Components (custom-elements and ShadowDom) sin preocuparnos de la version del navegador que estamos utilizando. Por ejemplo, actualmente Microsft Edge no soporta los custom-elements y tampoco soporta el shadowDom. Sin el utlizo de Stencil tendriamos que resolver el problema manualmente usando polyfills que no siempre tienen un buen rendimiendo.
