# Cuestionario: Frameworks de CSS y Metodología BEM

*A continuación, responde cada una de las siguientes preguntas. Recuerda hacer un commit por cada pregunta principal que completes.*

### Pregunta 1: Fundamentos de los Frameworks de CSS

* **1.1.** ¿Qué es un **Framework de CSS**? Explícalo con una analogía del mundo real que no sea de programación (por ejemplo, un kit de bloques de construcción, una plantilla para dibujar, etc.) para facilitar su comprensión.
* **1.2.** ¿Qué problemas principales vienen a solucionar los frameworks de CSS en el desarrollo web? Menciona y explica al menos dos ventajas clave de utilizarlos.

**[ESPACIO PARA TU RESPUESTA 1]**
1.1. Un Framework de CSS es como un kit de bloques de construcción o un set de piezas de LEGO: ya vienen hechas y listas para usar, de manera que puedas armar estructuras (páginas web) rápidamente sin tener que crear cada pieza desde cero.

1.2. Problemas que solucionan:

Consistencia de diseño: Evitan que los estilos se vean distintos en distintas páginas, al ofrecer reglas predefinidas.

Ahorro de tiempo: Permiten construir interfaces rápidas con componentes y clases listas.

Ventajas clave:

Desarrollo más rápido.

Mantenimiento más sencillo y menos errores de estilo.
---

### Pregunta 2: Bootstrap CSS - El Ecosistema Basado en Componentes

* **2.1.** Describe la filosofía principal de **Bootstrap**, centrada en **componentes pre-diseñados** (component-based).
* **2.2.** Investiga en la documentación de Bootstrap y crea una lista con **10 clases** fundamentales. Incluye el nombre de la clase y una breve definición de lo que hace. (Ej: `.container` - Centra y ajusta el ancho del contenido). Procura que la lista incluya clases de layout (grid), componentes y utilidades.
* **2.3.** Basado en tu investigación, menciona dos **ventajas** y dos **desventajas** claras de usar Bootstrap en un proyecto.

**[ESPACIO PARA TU RESPUESTA 2]**
2.1. Filosofía principal de Bootstrap
Bootstrap se basa en un enfoque component-based, lo que significa que ofrece componentes pre-diseñados que puedes usar directamente en tu proyecto, como botones, tarjetas, barras de navegación, tablas y formularios. Esto permite construir interfaces completas de manera rápida y consistente, sin tener que crear cada elemento desde cero.

2.2. 10 clases fundamentales de Bootstrap

Clase	Función / Descripción
.container	Crea un contenedor centrado y ajusta automáticamente su ancho según el tamaño de pantalla.
.row	Define una fila en el sistema de grillas (grid) de Bootstrap.
.col	Define una columna dentro de una fila; se adapta a distintos tamaños de pantalla.
.btn	Aplica estilos básicos a un botón.
.btn-primary	Aplica el estilo de botón principal de Bootstrap (color y padding).
.card	Crea un contenedor tipo tarjeta con sombra y padding.
.navbar	Define una barra de navegación responsive.
.text-center	Centra el texto horizontalmente.
.d-flex	Aplica display: flex; para crear layouts flexibles.
.alert	Muestra un mensaje de alerta con estilos predefinidos.

Estas clases incluyen layout (grid), componentes y utilidades, cubriendo la base de la mayoría de proyectos.

2.3. Ventajas y desventajas de usar Bootstrap

Ventajas:

Rápido prototipado: Permite crear páginas web completas en menos tiempo gracias a sus componentes listos.

Consistencia visual: Todos los elementos siguen un mismo estilo, evitando inconsistencias entre páginas.

Desventajas:

Código HTML más pesado: Usar muchas clases puede hacer que el HTML se vea saturado.

Limitada personalización: Para diseños muy únicos, puede ser difícil sobrescribir los estilos predeterminados.
---

### Pregunta 3: Tailwind CSS - El Enfoque "Utility-First"

* **3.1.** Describe la filosofía **"Utility-First"** (clases de utilidad) de **Tailwind CSS** y en qué se diferencia fundamentalmente del enfoque de Bootstrap.
* **3.2.** Investiga en la documentación de Tailwind y crea una lista con **10 clases** de utilidad. Incluye el nombre de la clase y el estilo CSS que aplica. (Ej: `.text-center` - Aplica `text-align: center;`). Procura que la lista incluya clases para manejo de colores, espaciado, tipografía y flexbox.
* **3.3.** Basado en tu investigación, menciona dos **ventajas** y dos **desventajas** claras de usar Tailwind CSS en un proyecto.

**[ESPACIO PARA TU RESPUESTA 3]**
3.1. Filosofía "Utility-First" de Tailwind CSS
Tailwind CSS sigue un enfoque "Utility-First", lo que significa que en lugar de usar componentes pre-diseñados como Bootstrap, se trabaja con clases de utilidad que aplican estilos específicos (márgenes, colores, tipografía, flexbox, etc.). Esto permite construir diseños personalizados combinando múltiples clases en el HTML.

Diferencia principal con Bootstrap:

Bootstrap: Componentes listos para usar (cards, buttons, navbars).

Tailwind: Clases pequeñas y combinables; tú construyes el diseño desde cero usando utilidades.

3.2. 10 clases de utilidad de Tailwind CSS

Clase	Estilo que aplica
.text-center	text-align: center;
.bg-blue-500	Fondo azul medio
.p-4	Padding de 1rem
.m-2	Margin de 0.5rem
.font-bold	font-weight: bold;
.text-lg	Tamaño de letra grande
.flex	display: flex;
.justify-between	justify-content: space-between;
.items-center	align-items: center;
.rounded	Bordes redondeados

Estas clases incluyen manejo de colores, espaciado, tipografía y flexbox.

3.3. Ventajas y desventajas de usar Tailwind CSS

Ventajas:

Flexibilidad total: Permite construir cualquier diseño combinando utilidades.

CSS eficiente: Solo se usan las clases necesarias, evitando código muerto.

Desventajas:

HTML más largo: El HTML puede verse saturado con muchas clases.

Curva de aprendizaje: Inicialmente puede ser difícil memorizar y combinar tantas clases de utilidad.
---

### Pregunta 4: BEM - Organizando CSS Puro

* **4.1.** ¿Qué es la metodología **BEM** (Block, Element, Modifier)? Explica con tus propias palabras qué representa cada una de sus partes (Bloque, Elemento y Modificador).
* **4.2.** ¿Qué problema clave viene a solucionar BEM en el desarrollo con CSS puro? ¿Cómo ayuda a prevenir colisiones de estilos y a hacer el código más mantenible?
* **4.3.** Muestra un ejemplo de código HTML y CSS para un componente de "tarjeta de producto" (`product-card`) utilizando la sintaxis BEM. El bloque debe tener elementos como un título, una imagen y un botón, y el botón debe tener un modificador para un estado primario (ej. `product-card__button--primary`).

**[ESPACIO PARA TU RESPUESTA 4]**
4.1. ¿Qué es BEM (Block, Element, Modifier)?
BEM es una metodología para organizar CSS y mantenerlo limpio y predecible. Sus partes son:

Block (Bloque): Es el contenedor principal o componente independiente (ej. product-card).

Element (Elemento): Son las partes internas del bloque, dependientes de él (ej. product-card__title, product-card__image).

Modifier (Modificador): Indica una variación o estado de un bloque o elemento (ej. product-card__button--primary para un botón principal).

4.2. Problema que soluciona BEM
BEM ayuda a prevenir colisiones de estilos al usar nombres únicos y estructurados para cada bloque y elemento. También hace que el código sea más mantenible, ya que puedes identificar claramente qué estilos pertenecen a cada componente y modificarlos sin afectar otros elementos.

4.3. Ejemplo de código HTML y CSS para "tarjeta de producto"

<div class="product-card">
  <h2 class="product-card__title">Nombre del producto</h2>
  <img class="product-card__image" src="producto.jpg" alt="Producto">
  <button class="product-card__button product-card__button--primary">Comprar</button>
</div>

.product-card {
  border: 1px solid #ccc;
  padding: 16px;
  width: 250px;
}

.product-card__title {
  font-size: 1.2rem;
  margin-bottom: 8px;
}

.product-card__image {
  width: 100%;
  height: auto;
  margin-bottom: 12px;
}

.product-card__button {
  padding: 8px 16px;
  background-color: gray;
  color: white;
  border: none;
  cursor: pointer;
}

.product-card__button--primary {
  background-color: blue;
}


Este ejemplo muestra cómo BEM organiza bloques, elementos y modificadores, haciendo que el CSS sea claro y fácil de mantener.
---

### Pregunta 5: Frameworks y CSS Puro - Conflictos y Convivencia

* **5.1.** ¿Es posible usar hojas de estilos personalizadas (CSS puro) junto a un framework? Explica las implicaciones y el orden en que deberían cargarse los archivos CSS en el HTML.
* **5.2.** Investiga sobre la **especificidad de CSS**. ¿Qué es y cómo puede generar conflictos al intentar sobreescribir un estilo de un framework? ¿Qué regla de estilo es más específica: la de una clase del framework (ej. `.btn-primary`) o una regla que tú escribas en tu CSS (ej. `#mi-boton-especial`)?
* **5.3.** ¿Es técnicamente posible y/o recomendable usar Bootstrap, Tailwind CSS y una hoja de estilos propia en un mismo proyecto? Argumenta sobre los posibles conflictos (ej. reseteo de estilos, colisión de nombres de clases) y problemas de rendimiento que esto podría causar.

**[ESPACIO PARA TU RESPUESTA 5]**
5.1. Uso de CSS propio junto a un framework
Sí, es posible usar hojas de estilos personalizadas junto a un framework como Bootstrap o Tailwind.

Implicaciones: Tus estilos pueden sobreescribir los estilos del framework si se cargan después en el HTML.

Orden de carga recomendado en <head>:

<link rel="stylesheet" href="bootstrap.css"> <!-- Framework -->
<link rel="stylesheet" href="tailwind.css">   <!-- Framework utility-first -->
<link rel="stylesheet" href="estilos.css">    <!-- CSS propio -->


Siempre carga tus estilos al final para que tengan prioridad sobre los estilos predeterminados del framework.

5.2. Especificidad de CSS
La especificidad determina qué regla CSS se aplica cuando hay varias posibles para un mismo elemento.

Reglas más específicas ganan:

ID (#mi-boton-especial) > Clase (.btn-primary) > Elemento (button)

Conflictos: Si intentas sobrescribir un estilo de un framework con una clase, puede que no funcione si el selector del framework es más específico.

Ejemplo: .btn-primary < #mi-boton-especial → el ID tiene prioridad.

5.3. Usar Bootstrap + Tailwind + CSS propio

Técnicamente posible: sí, pero no recomendable.

Posibles problemas:

Colisión de nombres de clases: dos frameworks pueden usar nombres similares (.btn, .container).

Reseteo de estilos: Tailwind aplica preflight que puede sobrescribir estilos de Bootstrap.

Rendimiento: carga de tres CSS grandes puede afectar velocidad de carga y renderizado.

Recomendación: si necesitas personalización máxima, usa un solo framework con CSS propio o BEM; evita mezclar varios frameworks pesados en un mismo proyecto.
---

### Pregunta 6: Comparación y Veredicto Final

* **6.1.** Crea una comparativa simple que resuma las diferencias clave entre Bootstrap, Tailwind CSS y una metodología como BEM para CSS puro. Considera al menos los siguientes criterios: **Curva de Aprendizaje**, **Nivel de Personalización**, **"Limpieza" del HTML** y **Velocidad de prototipado**.
* **6.2.** ¿En qué tipo de proyecto recomendarías usar **Bootstrap**? ¿En cuál **Tailwind CSS**? ¿Y en cuál optarías por **CSS Puro + BEM**? Justifica tu respuesta basándote en las fortalezas y debilidades de cada enfoque.

**[ESPACIO PARA TU RESPUESTA 6]**
6.1. Comparativa Bootstrap vs Tailwind CSS vs CSS Puro + BEM

Criterio	Bootstrap	Tailwind CSS	CSS Puro + BEM
Curva de Aprendizaje	Baja: fácil de usar con componentes listos	Media-alta: requiere aprender muchas clases de utilidad	Alta: requiere organizar y escribir CSS desde cero
Nivel de Personalización	Medio: se pueden sobrescribir estilos, pero limitado	Alto: gran flexibilidad combinando utilidades	Muy alto: control total sobre estilos y comportamiento
Limpieza del HTML	Media-baja: muchas clases en los componentes	Media-baja: HTML saturado de clases de utilidad	Alta: HTML limpio si se usan nombres claros con BEM
Velocidad de prototipado	Muy rápida: componentes listos	Media: flexible, pero requiere ensamblar utilidades	Lenta: todo se diseña desde cero

6.2. Recomendación de uso por tipo de proyecto

Bootstrap: Ideal para proyectos que necesitan prototipado rápido y consistencia visual sin mucha personalización, como landing pages, sitios institucionales o dashboards rápidos.

Tailwind CSS: Recomendado para proyectos que requieren diseño personalizado y flexibilidad, como aplicaciones web modernas donde cada componente tiene un estilo único.

CSS Puro + BEM: Perfecto para proyectos donde se necesita control total del código y mantenibilidad a largo plazo, como sistemas grandes o proyectos con equipos de front-end que necesitan evitar colisiones de estilos y mantener HTML limpio.

La elección depende de la rapidez del prototipo, la personalización y la complejidad del proyecto.