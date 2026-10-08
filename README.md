<div align="center">

# 🧬 Célula 3D · Eucariota y Procariota

**Modelo 3D interactivo y animado de la célula animal y la bacteria, con cada estructura señalada y explicada.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![three.js](https://img.shields.io/badge/three.js-r160-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![WebGL2](https://img.shields.io/badge/WebGL2-990000?style=for-the-badge&logo=webgl&logoColor=white)
![Sin internet](https://img.shields.io/badge/funciona-sin%20internet-7ee0a8?style=for-the-badge)

</div>

---

## ✨ ¿Qué es?

Una página web que muestra en 3D una **célula eucariota (animal)** y una **célula procariota (bacteria)**. Podés rotarlas, acercarte, cortarlas para ver el interior y hacer clic en cada parte para leer qué es y para qué sirve.

## 🔬 Qué incluye

| | |
|---|---|
| 🦠 **Dos células** | Eucariota animal y procariota bacteriana, con sus orgánulos y estructuras |
| 🏷️ **Etiquetas** | Cada estructura señalada con su nombre; clic para ver la ficha |
| ✂️ **Modo corte** | Abre la célula para mirar adentro |
| 🧭 **Recorrido guiado** | Pasa por todas las estructuras una por una |
| ⚖️ **Comparar** | Tabla de diferencias entre eucariota y procariota |
| 🎞️ **Animado** | Movimiento, brillo (bloom) e iluminación realista |
| 🖼️ **Vista 2D** | Ilustración plana estilo libro de texto, con zoom y las mismas fichas (botón **2D** arriba a la derecha) |

## 🚀 Cómo abrirlo

1. Descargá el repositorio (**Code → Download ZIP**) y descomprimilo.
2. Hacé doble clic en **`celula.html`**.

No necesita servidor ni internet: three.js y las tipografías vienen incluidos. Solo hace falta un navegador con **WebGL2** (Chrome, Edge o Firefox actualizados).

> 💡 Si movés el proyecto, llevá la carpeta completa: `celula.html` necesita `datos.js`, `lib/` y `fonts/` a su lado.

### 🖼️ Vista 2D

Con el botón **2D** de la barra superior (o la tecla `V`) se abre `celula2d.html`: la misma célula dibujada en plano, como en un libro de texto. Se mueve arrastrando, se acerca con la rueda, el pellizco o los botones **Acercar / Alejar**, y cada estructura tiene la misma ficha que en 3D. No necesita WebGL, así que anda en cualquier navegador. El botón **3D** vuelve al modelo y conserva la célula elegida.

## 🎮 Controles

| Acción | Mouse / táctil | Tecla |
|---|---|---|
| Rotar | Arrastrar | — |
| Acercar | Rueda o pellizco | — |
| Desplazar | Clic derecho | — |
| Ver información | Clic en la estructura | — |
| Cambiar de célula | — | `1` / `2` |
| Cambiar entre 3D y 2D | Botones **3D / 2D** | `V` |
| Corte | — | `C` |
| Etiquetas | — | `L` |
| Recorrido | — | `T` |
| Reiniciar vista | — | `R` |
| Pausa | — | `Espacio` |
| Estructura anterior / siguiente | — | `←` / `→` |
| Cerrar | — | `Esc` |

## 📁 Estructura

```
📄 celula.html        La página: modelos 3D, animaciones, textos e interfaz
📄 celula2d.html      Versión 2D: ilustración SVG interactiva
📄 datos.js           Textos de cada estructura (los usan las dos vistas)
📄 index.html         Entrada para GitHub Pages (redirige a celula.html)
📁 lib/               three.js r160 + complementos (órbita, bloom, entorno)
📁 fonts/             Tipografías Inter y Space Grotesk incrustadas
📄 LEEME.txt          Instrucciones detalladas
```

## 📜 Licencias

- [three.js](https://threejs.org/) — MIT (`lib/LICENSE-three.txt`)
- Inter y Space Grotesk — SIL Open Font License 1.1 (`fonts/OFL-*.txt`)
