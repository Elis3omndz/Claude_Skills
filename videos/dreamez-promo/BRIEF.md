---
workflow: product-launch-video
flow: automation
storyboard: yes
message: "Tu proyecto empieza con un formulario — y te respondemos al instante."
destination: instagram-reels
aspect: 1080x1920
language: es
audience: "Marcas, negocios y personas en El Salvador que buscan video, drone, fotografía o contenido digital"
length: 40s
angle: site-showcase
narration: yes
voice: ef_dora
---

## Intent

Anuncio para Instagram Reels de DREAMEZ (dreamezsv.netlify.app), estudio de
"Video · Drone · Fotografía · Contenido Digital" con el lema "Captura la realidad".
El propósito es "dar a conocer o resaltar los apartados de la web": todas las
secciones aparecen, pero el protagonista es el formulario de contacto
("Trabajemos Juntos"). Tono "entre moderno y corporativo". Mantener la paleta
de la web: "me gusta la tonalidad con la que la web ya cuenta".

Estructura confirmada: Gancho (Hero, ~3s) → Prueba (Campañas + Marcas, ~6s) →
Servicios (Tres modos + Galería, ~7s) → Equipo (~3s) → Formulario + flujo n8n +
correo (~16s) → CTA "Reserva tu sesión" + URL (~5s).

## Assets

- /home/user/dreamez — código fuente de la web (repo Elis3omndz/Dreamez), servido localmente para la captura; incluye logo-dreamez.png, logo-monograma.png, logos de marcas (marca-*.png), fotos de equipo, galería (serie-p*.jpg), hero-1..4.jpg y DREAMEZANIMATION.mp4.

## Customizations

- **v2 (pedido del usuario):** agregar narrador (voz Kokoro "Dora", femenina, español) y mostrar la web REAL dentro de dispositivos 3D (celular + laptop flotando) con elementos de la web que "saltan" fuera de la pantalla — estilo de su referencia de Pinterest (no accesible aquí; interpretación confirmada por el usuario). Tono "animado, divertido y llamativo".
- **Lenguaje simple:** NO decir "n8n" ni términos técnicos. Hablar del beneficio: "reservas tu sesión en segundos… y al instante te llega la confirmación a tu correo".

- Escena de automatización recreada (sin capturas del usuario): el formulario real de la web llenándose (Nombre, Correo, WhatsApp, Fecha, Servicio, Proyecto → "Enviar solicitud →"), luego un diagrama del flujo n8n (Formulario → n8n guarda el cliente → envía correo), y un correo de confirmación con la marca: "Recibimos tu solicitud, te contactaremos pronto."
- Sin música horneada: el usuario elegirá un audio en tendencia en Instagram al publicar (no hay HeyGen ni generador local disponible). Cortes con ritmo de ~105 bpm. Todo el mensaje en textos animados en pantalla. Sin voz en off.
- Diseño: la paleta y tipografías de la propia web — negro #0A0A0A / #111111, dorado #C9A84C / #E8C97A / #9A7A32, Playfair Display (títulos) + Montserrat (texto).

## Notes

- Las fotos de galería (serie-p*, hero-*, fotografia-flash) y los retratos del equipo son de stock/temporales: NO usarlos como portafolio ni como equipo. Usar solo capturas reales de la web, logos de clientes, la animación oficial del logo y tipografía.
- Netflix (serie-p2) excluido: marca de terceros.

- El dominio dreamezsv.netlify.app está bloqueado por la red de la sesión: capturar sirviendo /home/user/dreamez en localhost, viewport móvil.
- Hoy el formulario envía a Netlify Forms, no a n8n. El flujo n8n se muestra como explicación animada, no como grabación real. El usuario debe conectarlo antes de publicar.
- 9:16 vertical: los textos deben leerse en un celular; respetar las zonas seguras de la interfaz de Reels.
