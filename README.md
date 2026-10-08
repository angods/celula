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
| 🔎 **Estructura interna** | Modelos en corte de la mitocondria, el núcleo, la membrana plasmática, el aparato de Golgi y el motor del flagelo bacteriano, con cada componente explicado |
| 📚 **Con fuentes** | Textos revisados con bibliografía de referencia (ver *Fuentes* más abajo) |
| 🖼️ **Vista 2D** | Ilustración plana estilo libro de texto, con zoom y las mismas fichas (botón **2D** arriba a la derecha) |

## 🚀 Cómo abrirlo

1. Descargá el repositorio (**Code → Download ZIP**) y descomprimilo.
2. Hacé doble clic en **`index.html`**: se abre la vista **2D** (`celula2d.html`) y desde el botón **3D** se pasa al modelo 3D (`celula.html`).

No necesita servidor ni internet: three.js y las tipografías vienen incluidos. Solo hace falta un navegador con **WebGL2** (Chrome, Edge o Firefox actualizados).

> 💡 Si movés el proyecto, llevá la carpeta completa: las páginas necesitan `datos.js`, `lib/` y `fonts/` a su lado.

### 🖼️ Vista 2D

La página arranca en 2D (`celula2d.html`); con el botón **3D** de la barra superior (o la tecla `V`) se pasa al modelo 3D, y con **2D** se vuelve. La vista 2D es la misma célula dibujada en plano, como en un libro de texto. Se mueve arrastrando, se acerca con la rueda, el pellizco o los botones **Acercar / Alejar**, y cada estructura tiene la misma ficha que en 3D. No necesita WebGL, así que anda en cualquier navegador. Al cambiar de vista se conserva la célula elegida.

## 🎮 Controles

| Acción | Mouse / táctil | Tecla |
|---|---|---|
| Rotar | Arrastrar | — |
| Acercar | Rueda o pellizco | — |
| Desplazar | Clic derecho | — |
| Ver información | Clic en la estructura | — |
| Abrir la estructura interna | Botón **Estructura interna** de la ficha | `E` |
| Volver de la estructura interna | Botón **Volver** | `Esc` |
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
📄 index.html         Entrada (abre la vista 2D)
📁 lib/               three.js r160 + complementos (órbita, bloom, entorno)
📁 fonts/             Tipografías Inter y Space Grotesk incrustadas
📄 LEEME.txt          Instrucciones detalladas
```

## 📚 Fuentes

Los textos y los modelos se revisaron con estas fuentes. La lista también aparece en la ventana **Comparar**.

- Alberts B. y col. *Molecular Biology of the Cell*, 4.ª ed. (2002) — [NCBI Bookshelf](https://www.ncbi.nlm.nih.gov/books/NBK21054/)
- Cooper G. M. *The Cell: A Molecular Approach*, 2.ª ed. (2000) — [NCBI Bookshelf](https://www.ncbi.nlm.nih.gov/books/NBK9839/)
- OpenStax. *Biology 2e*, cap. 4: Cell Structure — [openstax.org](https://openstax.org/books/biology-2e/pages/4-introduction)
- Singer y Nicolson (1972), modelo de mosaico fluido — [Science](https://doi.org/10.1126/science.175.4023.720)
- Ou y col. (2017), ChromEMT: estructura de la cromatina en células — [Science](https://doi.org/10.1126/science.aag0025)
- Kühlbrandt (2015), complejos de la membrana mitocondrial — [BMC Biology](https://doi.org/10.1186/s12915-015-0201-x)
- Revisión sobre la arquitectura de las crestas mitocondriales (2021) — [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8306996/)
- Anderson y col. (1981), genoma mitocondrial humano — [Nature](https://doi.org/10.1038/290457a0)
- Ballabio (2016), *The awesome lysosome* — [EMBO Mol. Med.](https://doi.org/10.15252/emmm.201505966)
- Berg (2003), el motor rotatorio del flagelo bacteriano — [Annu. Rev. Biochem.](https://doi.org/10.1146/annurev.biochem.72.121801.161737)
- Magariyama y col. (1994), rotación flagelar muy rápida — [Nature](https://doi.org/10.1038/371752b0)

## 📜 Licencias

- [three.js](https://threejs.org/) — MIT (`lib/LICENSE-three.txt`)
- Inter y Space Grotesk — SIL Open Font License 1.1 (`fonts/OFL-*.txt`)
