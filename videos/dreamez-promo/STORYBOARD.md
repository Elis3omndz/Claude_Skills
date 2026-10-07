---
format: 1080x1920
duration: 40s
message: "Tu proyecto empieza con un formulario — y te respondemos al instante."
arc: Hook → Prueba → Servicios → Equipo → Demo del formulario (llenar → automatización → confirmación) → CTA
audience: Marcas, negocios y personas en El Salvador y Guatemala que buscan video, drone, fotografía o contenido digital
mode: collaborative
music: none
edit_tempo: cuts and reveals on a ~105 bpm grid (0.571s per beat) so a trending Instagram audio added at publish time sits naturally
language: es
---

# DREAMEZ — Reel promocional (9:16, ~40s)

No narration and no baked music (`music: none` + no SCRIPT.md = silent render): the
user adds a trending audio in Instagram when publishing. Every message is on-screen
text (the `onscreen` cues below are the pacing source — each `/` is one reveal).
No stock photos or stock portraits anywhere: only real site screens, client logos,
the official logo animation, and typography. Safe zones for Reels: keep
text out of the top ~220px and the bottom ~380px (caption + buttons overlay).

## Decisions (v1)

- **Spine — the gold thread:** one 1px gold hairline (#C9A84C) threads every beat: it
  underlines the hook, draws the logo grid, edges the service cards, becomes the form
  field underline, then the n8n connector, the email divider, and finally the CTA
  underline. It always travels upward/leftward (one direction rule, matching the scroll).
- **Brand (from capture):** ground #0A0A0A / #111111, ink #FFFFFF / #999999, gold
  #C9A84C (accent), #E8C97A (highlight), #9A7A32 (hairline). Display Montserrat 800,
  one accent word per headline in Playfair Display italic gold, labels Montserrat 500
  uppercase tracked. Square corners; the only pill is the CTA.
- **Held frame:** Frame 7 — the confirmation email lands and holds ~1.2s, nothing moving.
- **Bans:** no stock photos or portraits; no fake n8n editor UI (the flow is drawn as
  labelled abstract nodes); no glow blooms; no slideshow (every beat must carry the
  thread from the last); no screensaver motion; nothing inside the Reels keep-out
  (top 220px, bottom 380px).
- **Truthfulness:** Frames 1, 2, 4 show real captured screens and real client logos.
  Frame 5 rebuilds the real form 1:1 so it can animate (sample data "María López").
  Frames 6–7 depict the n8n automation as designed by the user; it must be live before
  the ad is published. Frame 8 plays the official logo animation.

## Timing (absolute)

| # | Beat | Start–end | Dur |
|---|------|-----------|-----|
| 01 | Captura la realidad | 0.0–3.5 | 3.5 |
| 02 | Marcas que ya confían | 3.5–9.0 | 5.5 |
| 03 | Tres modos de trabajar | 9.0–15.5 | 6.5 |
| 04 | El equipo | 15.5–19.0 | 3.5 |
| 05 | El formulario | 19.0–25.0 | 6.0 |
| 06 | La automatización | 25.0–31.0 | 6.0 |
| 07 | El correo llega | 31.0–35.5 | 4.5 |
| 08 | Reserva tu sesión | 35.5–40.5 | 5.0 |

Total 40.5s (target 40s).

Arc choice: a site showcase that pays off in a demo. The message is planted in
Frame 1 ("Tu proyecto empieza con un formulario") and the last half of the video
proves it — the site sections in between are the credibility that makes the form
worth filling.

## Frame 1 — Captura la realidad

- scene: The real hero screen of the site, slow push-in; a question lands, then the site's own tagline takes the frame
- onscreen: "¿Tu marca necesita contenido que venda?" / "CAPTURA LA REALIDAD" / "Video · Drone · Fotografía · Contenido digital"
- voiceover: ""
- duration: 3.5s
- poster: 2.6s
- transition_in: cut
- status: built
- src: compositions/frames/01-hook.html
- type: hook
- persuasion: Direct address
- beat: curiosity + aspiration
- blueprint: kinetic-type-beats
- asset_candidates: assets/00-hero.png — real mobile hero screen, "CAPTURA LA REALIDAD" over dark mountains

narrativeRole: Stop the scroll with a direct question to the brand owner, answered by the site's own promise.
keyMessage: DREAMEZ hace el contenido que tu marca necesita.

## Frame 2 — Marcas que ya confían

- scene: The "Campañas Destacadas" screen glides up and hands off to the 10 client logos assembling into a grid
- onscreen: "Campañas *Destacadas*" / "Restaurantes · Hotelería · Real estate · Marcas" / "Marcas con las que ha *colaborado*"
- voiceover: ""
- duration: 5.5s
- poster: 4.5s
- transition_in: crossfade
- status: built
- src: compositions/frames/02-marcas.html
- type: social_proof
- persuasion: Authority by association
- beat: trust
- blueprint: grid-card-assemble
- asset_candidates: assets/02-portfolio-0.png — real "Campañas Destacadas" screen with category filters; assets/03-collaborations-0.png — real 10-logo brand grid screen; assets/marca-la-casa-de-las-pupusas.png — client logo; assets/marca-kuskatan.png — client logo; assets/marca-guapollon.png — client logo; assets/marca-abel.png — client logo; assets/marca-barranko.png — client logo; assets/marca-vipros.png — client logo; assets/marca-sabor-del-cielo.png — client logo; assets/marca-la-casa-del-filete.png — client logo; assets/marca-la-pampa-centro-historico.png — client logo; assets/marca-emerino-realtor.png — client logo

narrativeRole: Prove they are real — named local brands already worked with them.
keyMessage: Restaurantes, hoteles y marcas reales ya trabajan con DREAMEZ.

## Frame 3 — Tres modos de trabajar

- scene: Four service words snap in on the beat, pure typography on black with a gold light sweep, then the three work modes stack as gold-hairline cards
- onscreen: "Video" / "Drone" / "Fotografía" / "Contenido digital" / "Tres modos de *trabajar*" / "Retrato de estudio" / "Editorial y campaña" / "Producto en negro"
- voiceover: ""
- duration: 6.5s
- poster: 5.5s
- transition_in: zoom-through
- status: built
- src: compositions/frames/03-servicios.html
- type: benefit_highlight
- persuasion: Value stacking
- beat: aspiration + confidence
- blueprint: kinetic-type-beats
- asset_candidates:

narrativeRole: Show the range — everything a brand needs under one roof.
keyMessage: Video, drone, foto y contenido, con un método claro.

## Frame 4 — El equipo

- scene: The real "El equipo DREAMEZ" screen; its three stats count up large in gold
- onscreen: "El equipo *DREAMEZ*" / "12+ años de experiencia" / "200+ proyectos completados" / "13 colaboraciones"
- voiceover: ""
- duration: 3.5s
- poster: 3s
- transition_in: crossfade
- status: built
- src: compositions/frames/04-equipo.html
- type: social_proof
- persuasion: Statistical proof
- beat: trust + confidence
- blueprint: dataviz-countup
- asset_candidates: assets/06-about-0.png — real "El equipo DREAMEZ" screen with the 12+ / 200+ / 13 stats (no portraits)

narrativeRole: Close the credibility section with the site's own numbers.
keyMessage: Experiencia comprobada: 12+ años, 200+ proyectos.

## Frame 5 — Trabajemos juntos (el formulario)

- scene: The site's real contact form, rebuilt 1:1 so it can move: fields fill in one by one, the "Video" chip lights gold, a tap on "ENVIAR SOLICITUD →"
- onscreen: "Tu proyecto empieza *aquí*" / "Nombre" / "Correo electrónico" / "Servicio: Video" / "ENVIAR SOLICITUD →"
- voiceover: ""
- duration: 6s
- poster: 5s
- transition_in: zoom-through
- status: built
- src: compositions/frames/05-formulario.html
- type: feature_showcase
- persuasion: Friction reduction
- beat: ease + control
- blueprint: device-surface-showcase
- asset_candidates: assets/07-contact-0.png — real "Trabajemos Juntos" form screen (layout reference for the rebuild); assets/07-contact-1.png — real bottom of form with the gold "ENVIAR SOLICITUD →" button; assets/form-filled.png — form crop with a typed email

narrativeRole: The hero beat — show how little it takes to start a project.
keyMessage: Llenar el formulario toma segundos.

## Frame 6 — La automatización trabaja

- scene: The submitted form shrinks into a node; a gold line runs Formulario → n8n → "Cliente guardado ✓" → "Correo enviado ✓", each step checking off
- onscreen: "Y en ese instante…" / "Formulario" / "n8n" / "Cliente guardado ✓" / "Correo de confirmación ✓" / "Automático. Sin esperas."
- voiceover: ""
- duration: 6s
- poster: 5.2s
- transition_in: crossfade
- status: built
- src: compositions/frames/06-automatizacion.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: curiosity → relief
- blueprint: agent-progress-theater
- asset_candidates:

narrativeRole: Reveal what happens behind the button — the client is saved and answered automatically.
keyMessage: Tu solicitud queda registrada y confirmada al instante, sin intervención manual.

## Frame 7 — El correo llega

- scene: A phone-style email notification drops in, then opens to a branded confirmation email
- onscreen: "DREAMEZ" / "Recibimos tu solicitud" / "Nos contactaremos contigo muy pronto." / "Respuesta al instante"
- voiceover: ""
- duration: 4.5s
- poster: 3.8s
- transition_in: push-slide UP
- status: built
- src: compositions/frames/07-correo.html
- type: benefit_highlight
- persuasion: Risk reversal
- beat: peace of mind
- blueprint: titlecard-reveal
- asset_candidates: assets/logo-dreamez.png — white wordmark for the email header; assets/logo-monograma.png — DM monogram as the sender avatar

narrativeRole: Pay off the message from the client's side — they get proof they were heard.
keyMessage: El cliente recibe confirmación inmediata en su correo.

## Frame 8 — Reserva tu sesión

- scene: The official DREAMEZ logo animation plays centered, then the CTA and URL settle under it
- onscreen: "Reserva tu *sesión*" / "dreamezsv.netlify.app"
- voiceover: ""
- duration: 5s
- poster: 4.5s
- transition_in: blur-crossfade
- status: built
- src: compositions/frames/08-cta.html
- type: cta
- persuasion: Urgency-to-act
- beat: motivation
- blueprint: logo-assemble-lockup
- asset_candidates: assets/DREAMEZANIMATION.mp4 — [video] official 8s logo animation, monogram + wordmark on black (play muted, center-cropped); assets/logo-dreamez.png — white wordmark fallback

narrativeRole: Turn attention into the single action — go to the site and fill the form.
keyMessage: Entra a la web y reserva tu sesión.
