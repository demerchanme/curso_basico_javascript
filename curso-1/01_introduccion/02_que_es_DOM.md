El DOM (Document Object Model) es un concepto fundamental que conecta HTML, CSS y JavaScript, 
permitiendo la interacción dinámica con las páginas web. 

¿Qué es el DOM?
Definición:
Es una representación en forma de árbol de los elementos de una página web. Cada elemento 
HTML (como etiquetas <div>, <p>, <img>, etc.) se convierte en un nodo dentro del árbol del DOM.

Propósito:
Permite que los lenguajes como JavaScript manipulen, accedan y modifiquen el contenido, la estructura 
y los estilos de la página en tiempo real.


Relación con HTML:
HTML es la base del DOM:
Cuando el navegador carga una página HTML, crea automáticamente el DOM a partir del código fuente.

Ejemplo:
Si tu archivo HTML tiene este código:

<!DOCTYPE html>
<html>
<head>
    <title>Ejemplo DOM</title>
</head>
<body>
    <h1 id="titulo">Hola, DOM</h1>
    <p class="texto">Este es un párrafo.</p>
</body>
</html>



El DOM creado será una estructura jerárquica como esta:


- html
  - head
    - title
  - body
    - h1 (id="titulo")
    - p (class="texto")



Relación con CSS:

CSS estiliza los nodos del DOM:
Los estilos que defines en tu archivo CSS o directamente en el HTML se aplican a los nodos del DOM.


Por ejemplo, este CSS:

h1 {
    color: blue;
}
p {
    font-size: 16px;
}


Cambia la apariencia de los nodos <h1> y <p> en el DOM.