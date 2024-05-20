
Este índice del Game Design Vault sirve como punto de partida para explorar todos los títulos  y sus respectivos subtítulos.

En lugar de un documento clásico, se optó por utilizar la plataforma Obsidian debido a la experiencia de usuario que ofrece. La navegación vertical tradicional de los documentos clásicos puede resultar tediosa y poco intuitiva. Obsidian, por otro lado, permite una navegación más horizontal y fluida, ==facilitando la exploración del contenido== por parte de los integrantes de otras áreas que deseen estar al día con los avances del proyecto. Además, al facilitar la referencia a otros fragmentos de información, ==se evita la repetición de datos== y se reducen las posibilidades de malentendidos.

Si bien la navegación horizontal es el enfoque principal, la navegación vertical no se elimina por completo. ==Cada nota tendrá hipervínculos al inicio y al final== para permitir a los usuarios saltar rápidamente a la entrada cronológica anterior o posterior. Nos enfocamos en crear una navegación intuitiva, adaptándonos a las preferencias del usuario.

Para estar al tanto de los últimos cambios realizados en la plataforma, basta con leer la descripción del último commit del repositorio Git creado para este proyecto. La nomenclatura utilizada para los cambios es la siguiente: "Actualización - [Título al que pertenece el cambio] - [Nota modificado]". Para quienes estén en el servidor de Discord del desarrollo del proyecto, hay un canal llamado "design-notif" en la categoría de Diseño. En este canal, cada vez que se actualice el repositorio, aparecerá una notificación junto al nombre del commit.

Para facilitar la navegación, se implementa un sistema de índices en cada título, similar al de esta nota, que desglosa el contenido en apartados.

**Índice**

| Orden |      Nombre      |         Link del índice          |
| :---: | :--------------: | :------------------------------: |
|   A   | Concepto general | [[1. Concepto general - Índice]] |
|   B   |  Sistemas y MDA  |  [[1. Sistemas y MDA - Índice]]  |
|   C   |  Mundo de juego  |  [[1. Mundo de juego - Índice]]  |
|   D   |     Interfaz     |     [[1. Interfaz - Índice]]     |
|   E   |       Arte       |       [[1. Arte - Índice]]       |
|   F   |      Audio       |      [[1. Audio - Índice]]       |

**Reglas**

Dado que la documentación y, especialmente, la navegación del GDV no son iguales a las de un documento clásico, se establecerán reglas que todos aquellos que editen el contenido de esta válvula deberán respetar.

1. La redacción siempre debe ser revisada ya sea por una inteligencia artificial o por uno mismo. La redacción debe ser impecable.
2. La información más importante debe subrayarse, aunque puede haber casos en los que la nota no contenga información que lo amerite. Como máximo, solo el 10% del texto total de la nota debe subrayarse.
3. Solamente se deben hacer referencias o hipervínculos a las notas que sean importantes para comprender el concepto o que estén directamente relacionadas con él. Menciones triviales no merecen hipervínculos.
4. Todas las imágenes adjuntas deben estar correctamente nombradas y ubicadas dentro de la carpeta de imágenes del título correspondiente.
5. Ninguna nota o imagen puede estar fuera de la carpeta "Game Design Vault".
6. Siempre debe haber una línea de separación entre el título y el cuerpo del texto. Del mismo modo, debe de haber una separación de una línea para con las imágenes adjuntadas. Al final del cuerpo del texto también debe haber dos líneas de separación con respecto a la sección de hipervínculos para volver.
7. Al final de cada nota deben incluirse los hipervínculos que permitan regresar al punto de origen para facilitar la navegación. La plantilla es: "Regresar: [Nota original]".
8. En caso de que un texto sea extenso y trate diferentes aspectos de una misma información, es recomendable dividirlo en secciones más pequeñas mediante incisos para facilitar la comprensión y la navegación. Algunos ejemplos podrían ser: Definición, Ejemplo y Aplicación práctica. Estos textos deben de ser destacados en negrita.
9. Las notas solo se dividirán en otras notas cuando sea necesario detallar información adicional. Es importante recordar que uno de los objetivos del GDV es evitar la repetición de información. Por lo tanto, si es probable que esas notas sean referenciadas en otras notas, es recomendable dividirlas y crear hipervínculos. De lo contrario, no es necesario y deberían mantenerse en la nota original.
10. Al dividir las notas, se añaden más subdivisiones al conteo. Por ejemplo, si la nota "1.3. Pilares" se divide en dos nuevas notas, estas serán "1.3.1" y "1.3.2". Este proceso se sigue de forma consecutiva con las divisiones subsiguientes.
11. Antes de comenzar a editar cualquier nota del documento, es importante avisar a los miembros del departamento de diseño que se estará trabajando en la válvula. Se debe especificar qué notas o títulos se desean reservar para permitir trabajar con libertad. En caso de que alguien más esté trabajando en alguna sección, se debe comunicar con esa persona para coordinar el trabajo de manera eficiente.
12. Siempre que alguien más realice un commit (se puede verificar en el canal "design-notif"), es necesario hacer un pull para sincronizar los cambios. Esto se puede hacer desde la consola de Git Bash o desde GitHub Desktop. Sin embargo, una forma más efectiva es desde Obsidian presionar "Control + P", escribir "pull" y seleccionar "Git: Pull".
13. En caso de que el nuevo commit entre en conflicto con su versión local del repositorio, deberá guardar su trabajo en un editor de texto, descartar todos sus cambios locales, actualizar el repositorio y luego reintegrar manualmente los cambios que había guardado previamente.
14. Antes de hacer push, debe revisar si Git ha registrado un cambio en un archivo que no ha editado. Si ese es el caso, debe descartar el cambio no deseado y luego hacer push.
15. Para hacer el push, deberá presionar "Control + P", luego escribir "backup" y seleccionar "Create backup with specific message". Después, debe ingresar el nombre de su push siguiendo el formato: "Actualización - [Título al que pertenece el cambio] - [Nota modificada]", y finalmente presionar Enter. Igualmente se pueden realizar estas actualizaciones desde la consola de Git bash o desde la interfaz de GitHub Desktop.
16. Lo más recomendable es hacer push cada vez que se termine de trabajar en una nota. De esta manera, se asegura de que su progreso esté guardado y, en caso de que se pierda, no perderá grandes cantidades de trabajo.


