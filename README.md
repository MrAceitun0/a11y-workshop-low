# a11y-workshop
Guía para el taller Coding Dojo: Rescatando webs inaccesibles paso a paso - estrenado en el [FresON Fest de Google Developers Group Aranjuez](https://fresonfest.gdg-aranjuez.com/)

Creado por: [Sergi Olives](https://www.linkedin.com/in/sergiolives/)

En este taller vamos a implementar accesibilidad en una web completamente inaccesible diseñada para este mismo taller. Siguiendo la web original vamos a ir analizando la accesibilidad usando herramientas de automatización como Lighthouse, Axe y Chrome DevTools para mejorar la experiencia de todos los usuarios.

[Google Slides](https://docs.google.com/presentation/d/1Ul1tQYMZodUqa-noJB60eDFFNd6UaU45ygP9c6SmAos/edit?usp=sharing)

## Configuración Inicial
1. Descarga este repositorio, vamos a trabajar con la carpeta **broken** - recomiendo hacer un **fork** del repositorio si tienes github
3. Instala la extensión de [Axe Dev Tools](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)
4. Inicia la web en un servidor HTTP

Opciones:
1. Usando Python
```
python3 -m http.server 8000
```
2. Usando NPX
```
npx serve solution
```
3. Usa la extensión en tu IDE de [LiveServer](https://open-vsx.org/extension/ritwickdey/LiveServer)


## Objetivo de hoy: Consigue que la web sea accesible
* Debes obtener una puntuación de 100 en Lighthouse
* Acaba con todos los problemas detectados en Axe DevTools
* Usa la web solo con teclado y ratón
* Usa la web con el VoiceOver - asegúrate de tener las voces descargadas para testear
  - en Mac **Option + Command + F5**
  - en Windows **Ctrl + Win + Enter**

## ¿Necesitas alguna pista? Siempre puedes consultar la carpeta SOLUTION
<details>
  <summary>Haz click aquí</summary>

  Put your hidden text, lists, or code blocks here.
</details>
