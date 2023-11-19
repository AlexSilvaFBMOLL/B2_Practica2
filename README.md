# CoinWorld

## Descripción
CoinWorld es una página web creada por Alex Silva cuya finalidad será organizar y preservar una colección de monedas y billetes de todo el mundo.

En una primera etapa, esta web se mantendrá de forma estática. Todo su contenido será introducido manualmente y siguiendo el curso de las explicaciones. En esencia, a medida que se vayan explicando más cosas esta web se actualizará para cumplir con las expectativas.

## Estructura de los archivos
Los archivos HTML se encuentran en la carpeta raíz, junto a este README y, posteriormente, se hayará también el manifest, utilizado por PWA.

Las carpetas creadas son autodescriptivas, es decir, con leer el nombre de éstas se puede saber qué hay en su interior. No obstante aquí dejo una lista con las diferentes carpetas:
```
Si pasas el ratón sobre los enlaces obtendrás más información sobre ellos.
```
+ [CSS](css "Archivos de estilo")
+ [Media](media "Contenido multimedia")
  + [Font](media/font "Fuentes de texto")
  + [SVG](media/svg "Imágenes vectoriales")

La estructura del proyecto es la siguiente:
```
proyecto
│   README.md
│   index.html    
│
└───css
│   │   index.css
│   
└───media
│   │
│   └───font
│   │   │   Gill-Sans-Bold.ttf
│   │   │   Gill-Sans.ttf
│   │
│   └───svg
│   │   │   CWLetters.svg
│   │   │   CWLettersDark.svg
│   │   │   Menu.svg
│   │   │   MenuDark.svg
```
## Tecnologías utilizadas
### Visual Studio Code
El proyecto se ha desarrollado con VSCode.
### Extensión Live Server
Con la extensión Live Server de VSCode, se ha testeado la página web en diversos dispositivos (móviles, portátiles) para poder mejorar la página según los resultados mostrados en cada uno de ellos.

Además, cada vez que se guardan los documentos editados, se actualizan automáticamente las pestañas de los navegadores.
### GitHub
Se ha trabajado en este proyecto en dos ordenadores, por lo que tener GitHub como repositorio no sólo ha ayudado a generar copias de seguridad, sino que ha permitido pasar archivos entre mis dos ordenadores para poder trabajar desde cualquiera de ellos.

También permite crear distintas ramas, por ejemplo: en el ordenador de sobremesa he creado una rama donde he implementado un manifest de la web, mientras que en el portátil estos cambios no aparecen porque aún no quiero que se implemente en la rama principal.

Por último, es una forma de compartir el proyecto con otras personas.
### SVGator
Mediante esta herramienta en línea gratuita, he diseñado algunos de los SVGs utilizados en este proyecto de manera fácil y rápida.
### Adobe Illustrator
Algunas de las funcionalidades de SVGator están limitadas, por lo que he aprovechado también este software para terminar de pulir los archivos vectoriales.

## Características y funcionalidades
### 18 de noviembre de 2023
+ Compatibilidad con modo claro y oscuro
+ Fuentes personalizadas
  + [Gill Sans](https://freefontsdownload.net/free-gill-sans-mt-font-37146.htm)
+ Barra de navegación con desplegable
  + Hecho con checkbox y label para hacerlo funcional con CSS, sin utilizar JavaScript
  + [Fuente de la idea](https://stackoverflow.com/questions/13630229/can-i-have-an-onclick-effect-in-css)
+ Logotipos e iconos del desplegable SVG
  + Diseñados en [SVGator](https://app.svgator.com/)
  + Modificados en Adobe Illustrator