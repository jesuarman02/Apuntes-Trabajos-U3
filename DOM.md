Lunes 29 de septiembre del 2023

**¿Qué es Dom?**

DOM es la sigla de "Document Object Model", que se traduce como "Modelo de Objetos del Documento". Es una representación programática de la estructura de un documento, generalmente un documento HTML o XML, que permite a los programas y scripts acceder y manipular dinámicamente el contenido, la estructura y el estilo de un documento web.

El DOM representa el documento como un árbol de objetos, donde cada elemento del documento (como encabezados, párrafos, enlaces, imágenes, etc.) se representa como un nodo en el árbol. Estos nodos pueden tener padres, hijos y hermanos, lo que refleja la estructura jerárquica del documento. Además, cada nodo puede tener propiedades y métodos que permiten a los desarrolladores interactuar con él de diversas formas, como cambiar su contenido, estilo o posición en la página.

El DOM es fundamental para la programación web, ya que permite a los desarrolladores crear páginas web interactivas y dinámicas mediante la manipulación de elementos HTML y la respuesta a eventos del usuario. JavaScript es uno de los lenguajes de programación más comunes que se utiliza para interactuar con el DOM en el lado del cliente de una aplicación web. Con JavaScript y el DOM, los desarrolladores pueden crear aplicaciones web interactivas y ricas en contenido.

¿Cuáles son las funciones que permite modificar el DOM?

1.- **Acceder a elementos:**

Para acceder a elementos en el DOM, se utilizan métodos como `getElementById` o `querySelector` para seleccionar elementos por su identificador único (ID) o por un selector CSS, respectivamente.

![[1.png]] 


2.- **Acceder a elementos padre/hijo:**

Puedes acceder a elementos padres e hijos de un elemento específico utilizando las propiedades `parentNode`, `childNodes`, `children`, `firstChild`, `lastChild`, entre otras.

![[Pasted image 20230925115626.png]]

3.- **Crear elementos:**

Puedes crear nuevos elementos HTML utilizando el método `createElement`, y luego configurar sus propiedades y contenido antes de agregarlos al DOM.

![[Pasted image 20230925115654.png]]

4.- **Añadir elementos al DOM:**

Una vez que hayas creado un nuevo elemento, puedes agregarlo al DOM utilizando métodos como `appendChild`, `insertBefore` u otros métodos relacionados con la manipulación de nodos.

![[Pasted image 20230925115723.png]]

5.- **Añadir / Eliminar clases:**

Puedes agregar o eliminar clases CSS en elementos HTML para cambiar su estilo y presentación.

![[Pasted image 20230925115757.png]]
![[Pasted image 20230925115817.png]]

6.- **Obtener atributos:**

Puedes obtener el valor de los atributos de un elemento utilizando el método `getAttribute`.

![[Pasted image 20230925115841.png]]

7.- **Escribir texto dentro de un elemento:**

Puedes modificar el contenido de texto de un elemento utilizando la propiedad `textContent` o `innerHTML`.

![[Pasted image 20230925115904.png]]

8.- **Modificar atributos:**

Puedes modificar los atributos de un elemento directamente accediendo a sus propiedades.

![[Pasted image 20230925120104.png]]

**Jquery**

jQuery es una biblioteca de JavaScript de código abierto que se utiliza para simplificar la manipulación del Document Object Model (DOM), el manejo de eventos, las animaciones y las solicitudes AJAX (Asynchronous JavaScript and XML) en el desarrollo web.

Las principales características y usos de jQuery incluyen:

1. **Selección de elementos del DOM:** jQuery proporciona una sintaxis sencilla y poderosa para seleccionar elementos HTML en una página web utilizando selectores similares a los de CSS. Esto permite a los desarrolladores encontrar y trabajar con elementos específicos en el DOM de manera eficiente.

2. **Manipulación del DOM:** jQuery facilita la manipulación de elementos del DOM, lo que permite agregar, eliminar y modificar elementos, cambiar contenido, atributos y clases con facilidad. Esto simplifica tareas comunes en el desarrollo web, como la actualización dinámica de una página.

3. **Manejo de eventos:** jQuery simplifica la asignación y gestión de eventos en elementos HTML. Puedes adjuntar manejadores de eventos a elementos y responder a acciones del usuario, como clics, movimientos del mouse, envíos de formularios, entre otros.

4. **Efectos y animaciones:** jQuery ofrece una variedad de efectos y funciones de animación que permiten crear transiciones suaves y efectos visuales en elementos HTML. Esto hace que sea más fácil agregar interactividad y mejorar la experiencia del usuario en una página web.

5. **Comunicación AJAX:** jQuery simplifica las solicitudes y respuestas AJAX, lo que permite cargar datos de forma asincrónica desde un servidor web sin tener que recargar la página completa. Esto es esencial para crear aplicaciones web dinámicas que actualizan contenido en tiempo real.

6. **Compatibilidad multiplataforma:** jQuery se ha diseñado para funcionar de manera consistente en múltiples navegadores web, lo que ayuda a superar las diferencias en la implementación del DOM y los eventos en los navegadores.

7. **Amplia comunidad y recursos:** Debido a su popularidad, jQuery cuenta con una gran comunidad de desarrolladores que contribuyen con plugins, documentación y tutoriales. Esto hace que sea más fácil encontrar soluciones a problemas comunes y aprender a utilizar la biblioteca.

Ejemplos de las funciones anteriores con Jquery

**1. Acceder a elementos:**
![[Pasted image 20230925123438.png]]

**2. Acceder a elementos padre/hijo:**
![[Pasted image 20230925123527.png]]

**3. Crear elementos:**
![[Pasted image 20230925123548.png]]


**4. Añadir a DOM elementos:**
![[Pasted image 20230925123627.png]]

**5. Añadir / Eliminar clases:**
![[Pasted image 20230925123700.png]]

**6. Obtener atributos:**
![[Pasted image 20230925123742.png]]

**7. Escribir texto dentro de un elemento:**
![[Pasted image 20230925123811.png]]

**8. Modificar atributos:**
![[Pasted image 20230925123842.png]]


