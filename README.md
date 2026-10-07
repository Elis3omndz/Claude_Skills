# Claude Skills — HyperFrames

Repositorio de skills para Claude Code. Actualmente contiene la skill
**HyperFrames** (by HeyGen): *escribes HTML, renderiza video.*

---

## ¿Qué es HyperFrames?

Un framework open-source para **convertir HTML + CSS + media + animaciones en
videos MP4 deterministas**, pensado para que un agente de IA (como Claude Code)
lo maneje por ti. En vez de editar video a mano, describes lo que quieres y el
agente escribe la composición, le pone timing, anima, agrega audio y renderiza.

No es una sola skill: son **21 skills conectadas**. La puerta de entrada es
`/hyperframes`, que entiende tu pedido y carga el flujo correcto.

### Lo que puedes crear
| Quiero... | Skill que se usa |
|-----------|------------------|
| Promo de un producto/sitio web | `/product-launch-video` |
| Explicar un tema (sin cara ni web) | `/faceless-explainer` |
| Video de un Pull Request de GitHub | `/pr-to-video` |
| Subtítulos sobre un video hablado | `/embedded-captions` |
| Overlays/lower-thirds sobre entrevista | `/talking-head-recut` |
| Motion graphic corto (logo, stat, título) | `/motion-graphics` |
| Video sincronizado con música | `/music-to-video` |
| Presentación / deck interactivo | `/slideshow` |
| Cualquier otra cosa / multi-escena | `/general-video` |
| Portar un proyecto Remotion | `/remotion-to-hyperframes` |

---

## Cómo usarla (VER → HACER)

### 1. VER — la skill ya está instalada
Las skills viven en `.claude/skills/`. Claude Code las detecta solo en este
repo; no tienes que instalar nada más para que el agente las conozca.

### 2. HACER — pídele un video
Empieza **siempre** por el router. Ejemplo real:

> Usando `/hyperframes`, crea un video de 10 segundos con un título que aparece
> en fade-in, un video de fondo y música suave de fondo.

El agente te hará 2–3 preguntas (duración, estilo, formato), escribirá el HTML,
lo animará y lo renderizará.

### 3. REPETIR — varía el pedido
Cambia duración, formato (vertical 9:16 para TikTok/Reels, 16:9 para YouTube),
colores o ritmo. Mismo patrón, distinto resultado.

### 4. EXPLICAR — lo que aprendiste
Un video HyperFrames = un archivo HTML donde el DOM declara el *timing* con
atributos `data-*` y la animación es "seekable" (se puede saltar a cualquier
frame). Esa es la idea central de todo el framework.

---

## Requisitos para renderizar de verdad

Las skills enseñan al agente a producir el video. Para **renderizar el MP4** en
tu máquina/sesión hace falta el CLI de HyperFrames:

```bash
# Node.js >= 22 requerido
npx hyperframes render        # renderiza la composición a MP4
npx hyperframes usage --json  # revisa cuánto uso te queda
```

- **No** necesitas API keys para lo básico.
- Opcional: `GEMINI_API_KEY` solo si capturas sitios web con descripción de
  imágenes por IA (~$0.001/imagen).

---

## Mantener las skills actualizadas

Este repo tiene una copia fija (snapshot) del set completo. Para traer la
versión más nueva desde el proyecto oficial:

```bash
npx hyperframes skills update            # set núcleo
npx skills add heygen-com/hyperframes --all   # set completo (21 skills)
```

- Fuente oficial: https://github.com/heygen-com/hyperframes
- Docs: https://hyperframes.heygen.com/introduction
- Licencia: Apache-2.0 (de HeyGen)

---

## Estructura

```
.claude/skills/
├── hyperframes/            ← router: empieza aquí
├── hyperframes-core/       ← contrato de composición (HTML + data-*)
├── hyperframes-animation/  ← animaciones (GSAP, Lottie, Three.js...)
├── product-launch-video/   ← + 9 flujos de creación
├── ...                     ← 21 skills en total
└── skills-manifest.json    ← metadata de referencia
```

## Consejo para sacarle el máximo
1. **Siempre arranca con `/hyperframes`** — no llames un flujo suelto; el router
   elige mejor que tú al principio.
2. **Dale un brief claro**: objetivo, duración, formato y tono en una frase.
3. **Itera corto**: pide primero un borrador de 5–10s, revísalo y luego escala.
4. Para redes sociales, pide explícitamente el formato (9:16, 1:1 o 16:9).
