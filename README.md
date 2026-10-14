<a id="top"></a>

<div align="center">

# 🎨 Catálogo de efectos para README

Todo lo que se puede mostrar en un README de GitHub, con el código listo para copiar.
Reemplazá `TU_USUARIO` y `TU_REPO` en cada ejemplo.

[`Texto animado`](#texto-animado) [`Banners`](#banners) [`Separadores`](#separadores) [`Badges`](#badges) [`Iconos`](#iconos) [`Estadísticas`](#estadisticas) [`Diagramas`](#diagramas) [`Markdown nativo`](#markdown-nativo) [`Tema claro/oscuro`](#tema)

</div>

> [!NOTE]
> GitHub bloquea CSS y JavaScript dentro de los README. Todos los efectos animados son **imágenes SVG** que cargan desde servicios externos (por eso conviene poner siempre un `alt`). Si un servicio se cae, esa imagen deja de verse.

> [!TIP]
> Cada ejemplo tiene el código en un desplegable. Ese desplegable también es un efecto (ver [Markdown nativo](#markdown-nativo)).

---

<a id="texto-animado"></a>

## ⌨️ Texto animado (Typing SVG)

Efecto de tipeo. Se controla con parámetros en la URL: `font`, `size`, `color`, `duration`, `pause`, `repeat`, `center`, `vCenter`, `width`, `height`, `lines`, `letterSpacing`, `background`, `multiline`, `random`.

**Tipeo simple**

<div align="center">
  <img alt="Texto con tipeo" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=36BCF7&center=true&vCenter=true&width=500&height=45&lines=Gestor+de+Gastos">
</div>

<details>
<summary>Ver código</summary>

```html
<div align="center">
  <img alt="Texto con tipeo" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=36BCF7&center=true&vCenter=true&width=500&height=45&lines=Gestor+de+Gastos">
</div>
```
</details>

**Varias frases que rotan**

<div align="center">
  <img alt="Frases rotativas" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=F75C7E&center=true&vCenter=true&width=600&height=40&lines=Registr%C3%A1+tus+gastos;Controlá+tus+gastos+fijos;Dividí+cuentas+con+amigos">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Frases rotativas" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=F75C7E&center=true&vCenter=true&width=600&height=40&lines=Registr%C3%A1+tus+gastos;Control%C3%A1+tus+gastos+fijos;Divid%C3%AD+cuentas+con+amigos">
```

Las frases se separan con `;` y los espacios van como `+`. Los acentos se codifican (`á` = `%C3%A1`, `í` = `%C3%AD`, `ó` = `%C3%B3`, `é` = `%C3%A9`, `ñ` = `%C3%B1`).
</details>

**Tipeo una sola vez** (queda fijo, no parpadea)

<div align="center">
  <img alt="Tipeo una vez" src="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&duration=2500&pause=1000&color=00FFD1&repeat=false&center=true&vCenter=true&width=500&height=50&lines=INSTALACI%C3%93N">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Tipeo una vez" src="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&duration=2500&pause=1000&color=00FFD1&repeat=false&center=true&vCenter=true&width=500&height=50&lines=INSTALACI%C3%93N">
```
</details>

**Tipografías** (cualquiera de [Google Fonts](https://fonts.google.com))

<div align="center">
  <img alt="Fira Code" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&color=CCA9DD&center=true&vCenter=true&width=420&height=30&lines=Fira+Code"><br>
  <img alt="Orbitron" src="https://readme-typing-svg.demolab.com?font=Orbitron&size=20&color=CCA9DD&center=true&vCenter=true&width=420&height=30&lines=Orbitron"><br>
  <img alt="Press Start 2P" src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=14&color=CCA9DD&center=true&vCenter=true&width=420&height=30&lines=Press+Start+2P"><br>
  <img alt="Lexend Giga" src="https://readme-typing-svg.demolab.com?font=Lexend+Giga&size=18&color=CCA9DD&center=true&vCenter=true&width=420&height=30&lines=Lexend+Giga"><br>
  <img alt="Pacifico" src="https://readme-typing-svg.demolab.com?font=Pacifico&size=24&color=CCA9DD&center=true&vCenter=true&width=420&height=40&lines=Pacifico">
</div>

<details>
<summary>Ver código</summary>

Solo cambia el parámetro `font` (con `+` en lugar de espacios):

```
?font=Orbitron
?font=Press+Start+2P
?font=Lexend+Giga
?font=Pacifico
```
</details>

**Espaciado, fondo y letras grandes**

<div align="center">
  <img alt="Espaciado y fondo" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&letterSpacing=8px&color=FFFFFF&background=7B2FF7&center=true&vCenter=true&width=500&height=50&lines=ARQUITECTURA">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Espaciado y fondo" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&letterSpacing=8px&color=FFFFFF&background=7B2FF7&center=true&vCenter=true&width=500&height=50&lines=ARQUITECTURA">
```
</details>

[`🡅`](#top)

---

<a id="banners"></a>

## 🌊 Banners (Capsule Render)

Encabezados y pies con formas, degradés y animación. Parámetros principales: `type`, `color`, `height`, `section` (`header` o `footer`), `text`, `fontSize`, `fontColor`, `animation`, `fontAlign`, `fontAlignY`, `desc`, `descSize`, `descAlign`, `descAlignY`, `reversal`, `stroke`, `strokeWidth`, `textBg`.

**Ola con degradé y animación `fadeIn`**

<div align="center">
  <img alt="Banner ola" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FF7,100:00FFD1&height=180&section=header&text=Gestor%20de%20Gastos&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Trabajo%20Final%20Integrador&descAlignY=58&descSize=18" width="100%">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Banner ola" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FF7,100:00FFD1&height=180&section=header&text=Gestor%20de%20Gastos&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Trabajo%20Final%20Integrador&descAlignY=58&descSize=18" width="100%">
```
</details>

**Otras formas** (`type=`)

<div align="center">
  <img alt="egg" src="https://capsule-render.vercel.app/api?type=egg&color=0:F75C7E,100:FFB86C&height=110&section=header&text=egg&fontSize=36&fontColor=fff" width="48%">
  <img alt="shark" src="https://capsule-render.vercel.app/api?type=shark&color=0:36BCF7,100:7B2FF7&height=110&section=header&text=shark&fontSize=36&fontColor=fff" width="48%">
  <img alt="slice" src="https://capsule-render.vercel.app/api?type=slice&color=0:00FFD1,100:36BCF7&height=110&section=header&text=slice&fontSize=36&fontColor=fff" width="48%">
  <img alt="soft" src="https://capsule-render.vercel.app/api?type=soft&color=0:7B2FF7,100:F75C7E&height=110&section=header&text=soft&fontSize=36&fontColor=fff" width="48%">
  <img alt="cylinder" src="https://capsule-render.vercel.app/api?type=cylinder&color=0:36BCF7,100:00FFD1&height=110&section=header&text=cylinder&fontSize=36&fontColor=fff" width="48%">
  <img alt="venom" src="https://capsule-render.vercel.app/api?type=venom&color=0:7B2FF7,100:36BCF7&height=110&section=header&text=venom&fontSize=36&fontColor=fff" width="48%">
</div>

<details>
<summary>Ver código</summary>

Cambiá `type=` por `waving`, `egg`, `shark`, `slice`, `soft`, `cylinder`, `venom`, `rect` o `transparent`:

```html
<img alt="shark" src="https://capsule-render.vercel.app/api?type=shark&color=0:36BCF7,100:7B2FF7&height=110&section=header&text=shark&fontSize=36&fontColor=fff" width="48%">
```
</details>

**Animaciones** (`animation=`): `fadeIn`, `scaleIn`, `blink`, `blinking`, `twinkling`

<div align="center">
  <img alt="twinkling" src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,100:302b63&height=90&section=header&text=twinkling&fontSize=34&fontColor=ffffff&animation=twinkling" width="48%">
  <img alt="scaleIn" src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,100:302b63&height=90&section=header&text=scaleIn&fontSize=34&fontColor=ffffff&animation=scaleIn" width="48%">
</div>

**Pie de página** (`section=footer`)

<div align="center">
  <img alt="Pie" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FF7,100:00FFD1&height=120&section=footer" width="100%">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Pie" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FF7,100:00FFD1&height=120&section=footer" width="100%">
```
</details>

[`🡅`](#top)

---

<a id="separadores"></a>

## ➖ Separadores

En lugar de `---`, una línea con degradé generada con Capsule Render:

<img alt="separador" src="https://capsule-render.vercel.app/api?type=rect&color=0:7B2FF7,100:00FFD1&height=3" width="100%">

<details>
<summary>Ver código</summary>

```html
<img alt="separador" src="https://capsule-render.vercel.app/api?type=rect&color=0:7B2FF7,100:00FFD1&height=3" width="100%">
```
</details>

Y una línea de puntos para secciones más suaves:

<p align="center">· · · · · · · · · · · ·</p>

[`🡅`](#top)

---

<a id="badges"></a>

## 🏷️ Badges (Shields.io)

**Estilos** (`style=`)

<div align="center">

![flat](https://img.shields.io/badge/estilo-flat-blue?style=flat)
![flat-square](https://img.shields.io/badge/estilo-flat--square-blue?style=flat-square)
![plastic](https://img.shields.io/badge/estilo-plastic-blue?style=plastic)
![for-the-badge](https://img.shields.io/badge/estilo-for--the--badge-blue?style=for-the-badge)

</div>

**Con logo y colores propios**

<div align="center">

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

**Dinámicos** (leen datos reales del repositorio)

<div align="center">

![Stars](https://img.shields.io/github/stars/TU_USUARIO/TU_REPO?style=social)
![Forks](https://img.shields.io/github/forks/TU_USUARIO/TU_REPO?style=flat-square)
![Issues](https://img.shields.io/github/issues/TU_USUARIO/TU_REPO?style=flat-square)
![Último commit](https://img.shields.io/github/last-commit/TU_USUARIO/TU_REPO?style=flat-square)
![Lenguaje](https://img.shields.io/github/languages/top/TU_USUARIO/TU_REPO?style=flat-square)
![Tamaño](https://img.shields.io/github/repo-size/TU_USUARIO/TU_REPO?style=flat-square)
![Licencia](https://img.shields.io/github/license/TU_USUARIO/TU_REPO?style=flat-square)

</div>

**Barras de progreso por fase** (badges estáticos)

<div align="center">

![Núcleo personal](https://img.shields.io/badge/N%C3%BAcleo%20personal-100%25-brightgreen?style=flat-square)
![Comprobantes](https://img.shields.io/badge/Comprobantes-60%25-yellow?style=flat-square)
![Gastos fijos](https://img.shields.io/badge/Gastos%20fijos-30%25-orange?style=flat-square)
![Eventos](https://img.shields.io/badge/Eventos-0%25-lightgrey?style=flat-square)

</div>

<details>
<summary>Ver código</summary>

```markdown
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Stars](https://img.shields.io/github/stars/TU_USUARIO/TU_REPO?style=social)
![Comprobantes](https://img.shields.io/badge/Comprobantes-60%25-yellow?style=flat-square)
```

Para que un badge sea un link: `[![texto](url-del-badge)](url-destino)`.
</details>

**Contador de visitas**

<div align="center">
  <img alt="Visitas" src="https://komarev.com/ghpvc/?username=TU_USUARIO&label=Visitas&color=7B2FF7&style=flat-square">
</div>

[`🡅`](#top)

---

<a id="iconos"></a>

## 🧩 Iconos de tecnologías

**Skill Icons** (una sola imagen con todos los íconos)

<div align="center">
  <img alt="Tecnologías" src="https://skillicons.dev/icons?i=angular,ts,nodejs,express,postgres,prisma,git,github&perline=8">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Tecnologías" src="https://skillicons.dev/icons?i=angular,ts,nodejs,express,postgres,prisma,git,github&perline=8">
```

Agregá `&theme=light` para la versión clara. Los nombres válidos están en [skillicons.dev](https://skillicons.dev).
</details>

**Simple Icons y Devicon** (íconos sueltos, con tamaño y color propio)

<div align="center">
  <img alt="Angular" src="https://cdn.simpleicons.org/angular/DD0031" width="48">
  <img alt="TypeScript" src="https://cdn.simpleicons.org/typescript/3178C6" width="48">
  <img alt="PostgreSQL" src="https://cdn.simpleicons.org/postgresql/4169E1" width="48">
  <img alt="Prisma" src="https://cdn.simpleicons.org/prisma/2D3748" width="48">
</div>

<details>
<summary>Ver código</summary>

```html
<img alt="Angular" src="https://cdn.simpleicons.org/angular/DD0031" width="48">
```

Formato: `https://cdn.simpleicons.org/<nombre>/<color-hex>`.
</details>

[`🡅`](#top)

---

<a id="estadisticas"></a>

## 📈 Estadísticas y widgets

> [!IMPORTANT]
> Estos widgets leen datos de tu **perfil** de GitHub. Tienen sentido en el README de tu perfil (el repo `TU_USUARIO/TU_USUARIO`), no en el de un proyecto.

**Estadísticas y lenguajes** (github-readme-stats)

<div align="center">
  <img alt="Stats" src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&theme=tokyonight&hide_border=true" height="150">
  <img alt="Lenguajes" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&theme=tokyonight&hide_border=true" height="150">
</div>

**Tarjeta de un repositorio**

<div align="center">
  <a href="https://github.com/TU_USUARIO/TU_REPO">
    <img alt="Tarjeta del repo" src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=TU_REPO&theme=tokyonight&hide_border=true">
  </a>
</div>

**Racha de contribuciones**

<div align="center">
  <img alt="Racha" src="https://streak-stats.demolab.com?user=TU_USUARIO&theme=tokyonight&hide_border=true">
</div>

**Gráfico de actividad**

<div align="center">
  <img alt="Actividad" src="https://github-readme-activity-graph.vercel.app/graph?username=TU_USUARIO&theme=tokyo-night&hide_border=true">
</div>

**Trofeos**

<div align="center">
  <img alt="Trofeos" src="https://github-profile-trophy.vercel.app/?username=TU_USUARIO&theme=onedark&no-frame=true&row=1&column=7">
</div>

**Frase aleatoria de programación**

<div align="center">
  <img alt="Frase" src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight">
</div>

**Contribuidores y evolución de estrellas** (esto sí sirve en el README de un proyecto)

<div align="center">
  <a href="https://github.com/TU_USUARIO/TU_REPO/graphs/contributors">
    <img alt="Contribuidores" src="https://contrib.rocks/image?repo=TU_USUARIO/TU_REPO">
  </a>
  <br><br>
  <a href="https://star-history.com/#TU_USUARIO/TU_REPO&Date">
    <img alt="Evolución de estrellas" src="https://api.star-history.com/svg?repos=TU_USUARIO/TU_REPO&type=Date" width="500">
  </a>
</div>

<details>
<summary>Ver código de todos los widgets</summary>

```html
<!-- Stats -->
<img alt="Stats" src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&theme=tokyonight&hide_border=true">

<!-- Lenguajes -->
<img alt="Lenguajes" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&theme=tokyonight&hide_border=true">

<!-- Tarjeta de repo -->
<img alt="Repo" src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=TU_REPO&theme=tokyonight">

<!-- Racha -->
<img alt="Racha" src="https://streak-stats.demolab.com?user=TU_USUARIO&theme=tokyonight">

<!-- Actividad -->
<img alt="Actividad" src="https://github-readme-activity-graph.vercel.app/graph?username=TU_USUARIO&theme=tokyo-night">

<!-- Trofeos -->
<img alt="Trofeos" src="https://github-profile-trophy.vercel.app/?username=TU_USUARIO&theme=onedark">

<!-- Frase -->
<img alt="Frase" src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight">

<!-- Contribuidores -->
<img alt="Contribuidores" src="https://contrib.rocks/image?repo=TU_USUARIO/TU_REPO">

<!-- Estrellas en el tiempo -->
<img alt="Estrellas" src="https://api.star-history.com/svg?repos=TU_USUARIO/TU_REPO&type=Date">
```

Los temas (`theme=`) disponibles incluyen `tokyonight`, `dracula`, `radical`, `gruvbox`, `onedark`, `synthwave`, `nord`.
</details>

**Serpiente que come tus contribuciones** (solo perfil)

Se genera con una GitHub Action ([Platane/snk](https://github.com/Platane/snk)) y se muestra como imagen.

<details>
<summary>Ver workflow (.github/workflows/snake.yml)</summary>

```yaml
name: Generar serpiente

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Y en el README:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/output/github-snake-dark.svg">
  <img alt="Serpiente" src="https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/output/github-snake.svg">
</picture>
```
</details>

[`🡅`](#top)

---

<a id="diagramas"></a>

## 🧭 Diagramas (Mermaid, nativo de GitHub)

No necesitan servicios externos: GitHub los dibuja a partir de texto.

**Flujo**

```mermaid
flowchart LR
    A[Frontend Angular] -->|HTTP / JSON| B[Backend Express]
    B --> C[(PostgreSQL)]
    B --> D[Job diario]
    D --> E[Recordatorios]
```

**Diagrama entidad-relación** (útil para tu documentación)

```mermaid
erDiagram
    USER ||--o{ EXPENSE : paga
    USER ||--o{ RECURRING_EXPENSE : define
    RECURRING_EXPENSE ||--o{ RECURRING_INSTANCE : genera
    EVENT ||--o{ EXPENSE : contiene
    EXPENSE ||--o{ EXPENSE_SPLIT : se_reparte_en
    USER ||--o{ EXPENSE_SPLIT : debe
    EVENT ||--o{ SETTLEMENT : liquida
```

**Secuencia**

```mermaid
sequenceDiagram
    actor U as Usuario
    participant F as Frontend
    participant B as Backend
    participant DB as PostgreSQL
    U->>F: Sube comprobante
    F->>B: POST /api/v1/receipts
    B->>B: OCR propone datos
    B-->>F: Propuesta
    U->>F: Confirma
    F->>B: POST /api/v1/expenses
    B->>DB: INSERT
    B-->>F: 201 Created
```

**Cronograma (Gantt)**

```mermaid
gantt
    title Fases del proyecto
    dateFormat YYYY-MM-DD
    section Núcleo
    Auth y gastos        :done, f1, 2026-10-14, 21d
    section Extras
    Comprobantes         :active, f2, after f1, 14d
    Gastos fijos         :f3, after f2, 14d
    Eventos y reparto    :f4, after f3, 21d
```

**Torta**

```mermaid
pie title Gastos por categoría
    "Comida" : 40
    "Transporte" : 20
    "Servicios" : 30
    "Ocio" : 10
```

<details>
<summary>Ver código del flujo y de la torta</summary>

````markdown
```mermaid
flowchart LR
    A[Frontend Angular] -->|HTTP / JSON| B[Backend Express]
    B --> C[(PostgreSQL)]
```

```mermaid
pie title Gastos por categoría
    "Comida" : 40
    "Transporte" : 20
```
````

Otros tipos: `classDiagram` (diagrama de clases), `stateDiagram-v2`, `gitGraph`, `journey`, `mindmap`, `timeline`.
</details>

[`🡅`](#top)

---

<a id="markdown-nativo"></a>

## ✍️ Markdown nativo

**Cajas de aviso**

> [!NOTE]
> Información útil que conviene tener a mano.

> [!TIP]
> Un consejo para hacer algo mejor o más fácil.

> [!IMPORTANT]
> Lo que sí o sí hay que saber.

> [!WARNING]
> Algo que puede traer problemas.

> [!CAUTION]
> Una acción con consecuencias graves.

<details>
<summary>Ver código</summary>

```markdown
> [!NOTE]
> Información útil que conviene tener a mano.
```

Cambiá `NOTE` por `TIP`, `IMPORTANT`, `WARNING` o `CAUTION`.
</details>

**Desplegables** (el efecto que usa todo este documento)

<details open>
<summary>Este arranca abierto</summary>

Contenido oculto que se muestra al hacer clic. Acepta Markdown adentro, incluso código y tablas.
</details>

<details>
<summary>Código</summary>

```html
<details>
<summary>Título</summary>

Contenido (dejá una línea en blanco después de summary).

</details>
```

Con `<details open>` arranca expandido.
</details>

**Fórmulas matemáticas** (LaTeX)

El balance neto de cada persona se calcula como:

$$\text{balance}_i = \text{pagado}_i - \text{corresponde}_i$$

En línea también funciona: la suma de los repartos debe ser igual a $monto$.

**Teclas, sub y superíndices, emojis y notas al pie**

Presioná <kbd>Ctrl</kbd> + <kbd>C</kbd>. Agua: H<sub>2</sub>O. Al cuadrado: x<sup>2</sup>. Emojis con atajos: :rocket: :moneybag: :tada:

Texto con nota al pie.[^1]

[^1]: Así se ve una nota al pie, que GitHub lleva automáticamente al final del archivo.

**Alineación y tamaño de imágenes**

<p align="right">Alineado a la derecha</p>
<p align="center">Alineado al centro</p>

<img alt="Imagen con tamaño" src="https://capsule-render.vercel.app/api?type=rect&color=7B2FF7&height=40" width="30%">

**Tabla con alineación por columna**

| Izquierda | Centro | Derecha |
|:---|:---:|---:|
| texto | texto | 1.200 |
| otro | otro | 35.000 |

**Lista de tareas**

- [x] Diseño de la arquitectura
- [x] Modelo de datos
- [ ] Autenticación
- [ ] Planilla de gastos

[`🡅`](#top)

---

<a id="tema"></a>

## 🌗 Tema claro y oscuro

Con `<picture>` mostrás una imagen distinta según el tema que use quien mira el README. Cambiá el tema de GitHub (Settings → Appearance) para verlo.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&color=CCA9DD&center=true&vCenter=true&width=500&height=40&lines=Estás+viendo+el+tema+oscuro">
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&color=7B2FF7&center=true&vCenter=true&width=500&height=40&lines=Estás+viendo+el+tema+claro">
    <img alt="Texto según el tema" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&color=7B2FF7&center=true&vCenter=true&width=500&height=40&lines=Tema+por+defecto">
  </picture>
</div>

<details>
<summary>Ver código</summary>

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="URL-imagen-oscura">
  <source media="(prefers-color-scheme: light)" srcset="URL-imagen-clara">
  <img alt="Descripción" src="URL-imagen-por-defecto">
</picture>
```

Sirve para logos, banners y capturas: una versión para cada tema.
</details>

[`🡅`](#top)

---

<div align="center">
  <img alt="Pie" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FF7,100:00FFD1&height=100&section=footer" width="100%">
</div>
