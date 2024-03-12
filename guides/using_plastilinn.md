# Using Plastilinn

[Plastilinn app](https://xbokmd.github.io/plastilinn/app.html)

En plastilinn Todo gira en torno a tu plastilinn doc, Que es un único documento donde Está Tu modelo de negocio completo.

Un modelo de negocio es una representación simplificada de la lógica que hace que un Negocio sea rentable. Es decir, Tu modelo de negocio se plasma en tu plastilinn doc, Que es un documento que recoge toda la información relevante sobre tu negocio. Incluye información sobre quienes son tus clientes
, Qué problemas les ayudas a resolver,, Qué canales vas a utilizar para Que te conozcan, etc...

Un plastilinn doc No es más que un fichero de texto plano en formato Mark Down.

- Texto plano: Los ficheros de texto plano son los más sencillos que hay Y se pueden editar con cualquier editor de texto . Todos los sistemas operativos tienen por defecto un editor de texto plano (Por ejemplo notepad de Windows), Por lo que al utilizar este formato de fichero nos aseguramos de que siempre sea editable independientemente del sistema operativo o en torno que utilice el usuario. Podrás editarlo tanto en Windows, Mac, Linux...
- Markdown: Markdown es un lenguaje de marcado ligero diseñado para ser fácil de escribir y leer. Se caracteriza por su simplicidad, permitiendo a los usuarios formatear texto usando una serie de símbolos y caracteres sencillos, como asteriscos para negrita y guiones bajos para cursiva, entre otros. La gran ventaja de Markdown es que permite concentrarse en el contenido del texto sin distracciones, facilitando la creación de documentos bien estructurados y legibles tanto en su forma cruda como en su versión final, una vez convertidos a HTML u otros formatos. Esto lo hace especialmente popular para la redacción de documentación técnica, archivos README en proyectos de software, y para autores de contenido en plataformas de blogs y sistemas de gestión de contenidos que buscan una forma eficiente y accesible de escribir.
- Almacenamiento local: Tu documento Se guarda en un tu disco duro Como Otros documentos con los que trabajas. Dentro de tu carpeta "Plastilinn" de tu disco duro estan Almacenados Tanto la versión actual de tu documento Cómo versiones anteriores. Otras herramientas similares a plastilinn Trabajan con un modelo de software como servicio(SaaS), En el que tu información se guarda en una base de datos en la nube, Y está controlada por la empresa que provee el servicio, Por lo que estás atado a ellos y puedes Perder el acceso a la información que has creado en el servicio si deciden subir los precios, Quieres dejar de pagar el servicio por cualquier motivo, O cierra la empresa proveedora del servicio.

## Modelos de negocio estructurado

Un plastilinn doc Te permite describir tu modelo de negocio de forma estructurada. Tú podrías describir tu modelo de negocio simplemente escribiendo un documento que de forma narrativa (Como si fuera una novela) Describe la lógica mediante la cual tu negocio gana dinero. Pero En ese formato no puedes aprovechar la información. En cambio en plastilinn Tu modelo de negocio se describe Utilizando Una estructura predefinida, Que utiliza los siguientes componentes:

| Tipo            | Descripción                                                                                              | Elemento y Descripción                                                                                                                                                                                  | Ejemplos                                                                                                                                                                                                                                                                                                                                                               |
|-----------------|----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sección**     | Unidades de contenido que describen aspectos específicos del modelo de negocio.                           | **Mission:** Propósito fundamental de la organización.<br>**Profile Name - Goals:** Problemas, necesidades o deseos que tienen los stakeholders relevantes para el negocio.<br>**Revenue Lines:** Fuentes de ingreso generadas por el negocio. | **1. Mission:** "Hacer que la vida humana sea multiplanetaria".<br>**2. Profile Name - Goals (Clientes de lanzamiento de satélites):** Reducir costos de lanzamiento, Aumentar la fiabilidad de los lanzamientos, Expandir la cobertura global de internet vía satélite.<br>**3. Revenue Lines:** Lanzamientos comerciales, Contratos con agencias gubernamentales, Servicios de internet vía Starlink. |
| **Clase**       | Elementos que representan conceptos o componentes clave dentro del modelo de negocio.                     | **Key:** Elementos críticos para el éxito.<br>**Solution:** Soluciones ofrecidas.<br>**Offering:** Propuesta de valor.                                                                                     | **1. Key:** Tecnología de cohetes reutilizables.<br>**2. Solution:** Desarrollo del Starship para misiones a Marte.<br>**3. Offering:** Servicios de lanzamiento para satélites y cargas útiles al espacio.                                                                                                                                                                                        |
| **Marcador**    | Indicadores o notas que ayudan a evaluar, clasificar o priorizar componentes del modelo de negocio.       | **Weight:** Importancia de componentes.<br>**Priority:** Urgencia de desarrollo.<br>**Certainty:** Confiabilidad del componente.                                                                          | **1. Weight:** Tecnología de cohetes reutilizables tiene un peso "*****".<br>**2. Priority:** Desarrollo del Starship tiene una prioridad "!!!!!".<br>**3. Certainty:** Viabilidad de cohetes reutilizables se marca con "=".
                                                                                                                                                                                                   |

[Plastilinn ocumentation](https://xbokmd.github.io/plastilinn/index.html#/)

## Editando tu plastilinn doc

Puedes editar tu plastilinn doc Directamente en la aplicación
https://stackedit.io/app#



## Export content

En cualquier momento puedes exportar tu documento como HTML Pulsando en el botón "export" de la esquina superior derecha. Tu documento se exportará como HTML limpio que puedes abrir, importar, o copiar y pegar en tu editor de documentos favorito (MS Word, Google Docs, etc...). El siguiente <a href="https://drive.google.com/drive/folders/1IbMu1j6hqWG0BLllePYftHpzubjxCEQy?usp=sharing" target="_blank">enlace abre una carpeta de Google Drive en la que puedes ver una muestra de todos estos documentos</a>.

## xBoK

El metamodelo describe la estructura y los elementos esenciales que deben contemplarse al diseñar y analizar modelos de negocio. Esta estructura incluye componentes como "key", "organization", "journey", "assumption", "solution", "offering", y muchos más, cada uno con su propio símbolo, color y definición detallada. Estos elementos cubren una amplia gama de aspectos críticos de un negocio, desde los recursos clave y las actividades hasta las propuestas de valor, los segmentos de clientes y las relaciones con los mismos.

Por ejemplo, el término "key" hace referencia a los componentes esenciales que son cruciales para el éxito del negocio, como pueden ser los recursos, las actividades, los socios o las propuestas de valor clave. "Organization" se refiere a la estructura y disposición de la empresa, abarcando cómo se distribuyen y coordinan las tareas, responsabilidades y recursos. "Journey" describe el proceso o camino que sigue un cliente desde que toma conciencia de un producto o servicio hasta que realiza la compra y más allá.

Además, el metamodelo incluye "markers" que permiten calificar ciertos aspectos como la importancia, la finalización, la prioridad, la certeza y el riesgo de los diferentes bloques de construcción del modelo de negocio. También se contemplan secciones que abordan el resumen del negocio, la idea de negocio, las oportunidades, la inspiración detrás del modelo, el estado actual del negocio, los desafíos, ventajas injustas, objetivos de negocio, misión, visión, estrategia, valores de la organización y más.

Este metamodelo es una herramienta integral diseñada para facilitar el análisis profundo y la construcción de modelos de negocio robustos y bien fundamentados, considerando todos los aspectos clave que pueden influir en su éxito y sustentabilidad en el mercado.