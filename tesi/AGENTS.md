# Criterios de trabajo para esta tesis

Estas pautas recogen las preferencias expresadas por Pedro para este proyecto.

## Colaboración y edición

- Trabajar y conversar en español.
- Pedro quiere ser quien principalmente edite y redacte la tesis. Priorizar observaciones, explicaciones matemáticas, propuestas de estructura y fragmentos sugeridos en la conversación.
- Avisar antes de hacer cualquier cambio en los archivos. No interpretar una consulta o una propuesta de redacción como autorización para aplicarla al documento.
- Modificar el texto de la tesis cuando Pedro solicite la edición; conservar su voz y las modificaciones que ya haya realizado.
- Hacer los cambios de redacción directamente en `tesis.tex`. No preparar secciones en archivos `.tex` auxiliares para después volcarlas al documento, porque eso dificulta que Pedro siga los cambios en el editor.
- No modificar nada fuera de la sección que Pedro indique, salvo indicación explícita. Avisar de un cambio no sustituye esa autorización. Las correcciones detectadas en otras secciones quedan para cuando Pedro pida revisarlas.
- Antes de editar, indicar concretamente qué pasajes de la sección autorizada se van a modificar. No hacer correcciones adicionales silenciosas ni presentarlas solamente como «ajustes de referencias».
- Al final de cada mensaje, incluir un resumen de los cambios; si no se modificó nada, decirlo. En la respuesta final, enumerar los pasajes modificados con sus ubicaciones y distinguir incorporaciones, traslados y correcciones. No mezclar cambios previos de Pedro con los realizados por el asistente.
- Aplicar las ediciones directamente mediante parches sobre los archivos autorizados, de modo que todos los cambios puedan revisarse en el diff de Codex.
- Revisar las secciones gradualmente. Atender los pendientes señalados con `\textbf`, sin asumir que todo texto en negrita es un pendiente.

## Objetivo y organización

- La tesis debe funcionar como un manual para producir los resultados matemáticos que estudia, con las demostraciones correspondientes.
- Mantener dos recorridos de lectura claros: uno con desarrollo y demostraciones, y otro práctico que permita aplicar los resultados como caja negra.
- Incluir la mayor parte de los ejemplos en el cuerpo de las secciones, junto a los conceptos y técnicas que ilustran.
- Explicar para qué sirve cada herramienta antes de enunciarla. Evitar generalidad y notación nuevas cuando no ayuden a la aplicación; usar la notación de Pedro, como `\OO_K` para el anillo de enteros.
- Escribir los operadores matemáticos en español: `\operatorname{gr}` para grado, `\operatorname{nu}` para núcleo y `\operatorname{rg}` para rango, en lugar de `deg`, `ker` y `rank`. Distinguir el operador `nu` de la letra griega `\nu`, que puede usarse para valuaciones.
- Incluir recapitulaciones prácticas con hipótesis, datos necesarios, pasos de aplicación y alcance de las conclusiones, remitiendo a los resultados demostrados.
- Cuidar el orden, las dependencias entre resultados y las referencias internas; eliminar repeticiones innecesarias sin suprimir recapitulaciones útiles.
- Incorporar referencias pertinentes a conjeturas y heurísticas, distinguiéndolas de los resultados demostrados.

## Fuentes y rigor

- Utilizar los papers y PDF aportados por Pedro y verificar las referencias antes de atribuirles resultados o ejemplos.
- Al proponer incorporar material, indicar la fuente y, cuando se haya comprobado, la sección, proposición o página correspondiente.
- Distinguir ejemplos de una fuente de ejemplos calculados específicamente para la tesis.
- Explicitar las hipótesis y distinguir condiciones necesarias, suficientes y equivalencias, especialmente en los argumentos locales y de descenso.

## Biblioteca del proyecto y prioridades

- Los PDF están en `Bibliografia/` (con mayúscula inicial). No modificar los originales.
- Los trabajos de Zywina, Koymans–Pagano y Ben Savoie son las fuentes principales y la guía del trabajo. La tesis contiene un resultado propio del mismo estilo, mediante 3-descenso en lugar de 2-descenso, siguiendo especialmente el enfoque de Savoie. No atribuir ese resultado propio a las fuentes ni dar por verificada su novedad por la sola lectura del borrador.
- Los dos textos de Stoll, `Bibliografia/Stoll-1Descent.pdf` y `Bibliografia/Stoll-2howToPDescent.pdf`, también son fuentes principales, muy cercanas al enfoque de la tesis. Antes de desarrollar o dar por revisado cada tema, consultar detenidamente las partes pertinentes de ambos textos; no omitir esta comprobación al trabajar con las demás fuentes.
- Los libros de Silverman en `Bibliografia/Libros/` son la referencia habitual. Aumentar las citas precisas de los resultados utilizados, comprobando su numeración en el PDF y la edición correspondiente.
- Preferir ejemplos de la familia estudiada en la tesis para reutilizarlos después. Sustituir una repetición en otra sección por una referencia interna solamente cuando Pedro autorice explícitamente editar también esa sección.
- `Bibliografia/Libros/ShiodaSuperficies.pdf` y `shiodaRemarks.pdf` son fuentes para un futuro desarrollo sobre superficies K3; ver `TODO.md`.
- `Bibliografia/elkies/` sirve principalmente para referencias de contexto en las introducciones y comentarios al final de los capítulos.
- `Bibliografia/Misc3desc/` reúne referencias complementarias sobre 3-descenso: incorporar citas y comentarios pertinentes, sin convertir todo ese material en parte del desarrollo principal.
- `Bibliografia/MiscCurvas/` queda para una etapa posterior, sobre curvas de rango alto.
- `Bibliografia/ParaCap4/` todavía se está completando. Esperar las indicaciones de Pedro antes de desarrollar el capítulo 4 con estas fuentes.

## Punto de partida acordado

- Comenzar por «Espacios homogeneos asociados» en `tesis.tex`.
- Orientar esta sección a aprender a descartar clases candidatas al grupo de Selmer mediante obstrucciones locales en sus espacios homogéneos asociados.
- Dar ejemplos prácticos, con Silverman y los trabajos de Zywina como fuentes propuestas, y enlazar las herramientas generales con el 3-descenso sobre `Q(omega)` que desarrolla la tesis.
