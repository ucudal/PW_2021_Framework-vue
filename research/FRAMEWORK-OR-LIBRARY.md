[Volver](README.md)

# ¿Framework o librería?

## Librería
Una librería define un conjunto de operaciones ya implementadas para utilizar en nuestra solución; o dicho de otra forma, resuelve pequeños problemas que no tenemos que implementar. En el control de flujo de nuestra aplicación, simplemente utilizamos estas operaciones para resolver un problema mayor, pero el control de flujo está definido por el programador. En otras palabras, nuestro código ejecuta a la librería, pero no al revés.

## Framework
En un framework, generalmente se utiliza la inversión de control o “IoC“ (inversion of control). Con IoC, el control de flujo ya está definido por el framework, y el programador diseñando la solución debe “llenar” los espacios en blanco necesarios para consolidar el flujo; siendo algunos de estos mandatorios, como por ejemplo definir algún módulo/componente de punto de entrada a la aplicación, y otros tantos opcionales, como podría ser definir acciones adicionales al montar un componente. En otras palabras, básicamente el framework ejecuta nuestro código, pero a su vez un framework utiliza ciertas librerías para su funcionamiento.

## ¿Qué ocurre con Vue?
Vue en particular está diseñado para funcionar como un framework, similar a otros frameworks como Angular. Lo particular de Vue (aunque no está recomendado al 100%) es que también puede ser “embebido” y utilizado como una librería de propósito similar, algo similar a jQuery. Según lo investigado, si bien esto último es posible, no está recomendado ya que existen ciertos problemas en aplicaciones escalables que utilizan otros frameworks y/o alguna otra versión de Vue.
