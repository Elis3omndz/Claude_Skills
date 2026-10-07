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

## Locked

- v1 sketch sheet (`storyboard.html`) confirmed by the user without changes: all 8 layouts, copy, palette and seams are locked.

## Video direction

- **Palette by role (frame.md):** ground bg-primary #0A0A0A on every frame (Frame 8 sits on pure #000 so the official logo clip's black matches); surfaces bg-secondary #111111; type text-primary #FFFFFF, support text-secondary #999999; ONE accent: gold #C9A84C (headline accent word, the thread, selected states, check marks); line #9A7A32 for hairlines/borders; #E8C97A only for the CTA URL text.
- **Type by role:** display/h1/h2 Montserrat 800 with one accent word in Playfair Display italic gold per headline; labels Montserrat 500 uppercase, tracked; stats Montserrat 800 in gold.
- **Motion grammar:** long-tail power3 settles everywhere, expo.out on fast arrivals; never bounce/back/elastic. Silent film: every reveal lands on the ~105 bpm grid (beat = 0.571s) instead of a voiceover cue, so a trending audio added in Instagram sits on the cuts. Reveal sequentially across each shot; nothing front-loaded.
- **The gold thread (spine):** a 1px-equivalent (3px at 1080) gold line drawn with a left-to-right scaleX wipe appears in every frame as the first or the connecting move — hook underline, grid rules, card edges, the active form-field underline, the n8n connector, the email divider, the CTA pill outline.
- **Rhythm / holds:** Frames 1–4 are brisk (reveal every 1–2 beats). Frame 5 slows to a typing tempo. Frame 6 builds. Frame 7 is the deliberate HELD frame (~1.2s of stillness after the email lands). Frame 8 lets the logo animation breathe, then lands the CTA.
- **Negative list:** no stock photos/portraits; no fake n8n editor UI; no glow blooms or lens flares; no purple/blue gradients; no cursor arrows (a tap ring only); no bouncy easing; no lazy breathing or back-half drift (subtle jitter is the only aliveness); no slideshow (front-load then freeze) and no screensaver (many things floating); nothing below y=1540 or above y=220 except the full-bleed screenshots themselves.

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
- status: animated
- src: compositions/frames/01-hook.html
- type: hook
- persuasion: Direct address
- beat: curiosity + aspiration
- blueprint_candidate: kinetic-type-beats
- asset_candidates: assets/00-hero.png — real mobile hero screen, "CAPTURA LA REALIDAD" over dark mountains

narrativeRole: Stop the scroll with a direct question to the brand owner, answered by the site's own promise.
keyMessage: DREAMEZ hace el contenido que tu marca necesita.

- blueprint: kinetic-type-beats (Adapt)
- focal: assets/00-hero.png
- roles: 00-hero = background (full-bleed real screen, top ~30% darkened with a gradient so the question reads; its own "CAPTURA LA REALIDAD" stays fully legible)
- sfx: none

Adapt: keep the word-by-word kinetic statement landing a payoff; the payoff is the site's own headline already on the screenshot, so the question hands focus down to it instead of a logo.
Scene 1 (0.0–0.6s): the hero screenshot is already on screen at 1.06 scale and starts a slow push-in toward 1.0 across the whole frame (multi-phase-camera, single phase — the only camera move). Label "DREAMEZ · PRODUCCIÓN AUDIOVISUAL" fades up in the upper third.
Scene 2 (0.6–2.0s): the question "¿Tu marca necesita contenido que venda?" assembles word by word on the beat (dynamic-content-sequencing), upper third, left-aligned, the last word "venda?" in Playfair italic gold arriving last; then the gold thread wipes in under it left→right.
Scene 3 (2.0–3.5s): hold the full read — the question above, the site's "CAPTURA LA REALIDAD" below; the darkening gradient over the screenshot's headline lifts slightly so the headline brightens on the 2.3s beat (keyword emphasis by contrast, not glow). Subtle jitter at most.

## Frame 2 — Marcas que ya confían

- scene: The "Campañas Destacadas" screen glides up and hands off to the 10 client logos assembling into a grid
- onscreen: "Campañas *Destacadas*" / "Restaurantes · Hotelería · Real estate · Marcas" / "Marcas con las que ha *colaborado*"
- voiceover: ""
- duration: 5.5s
- poster: 4.5s
- transition_in: crossfade
- status: animated
- src: compositions/frames/02-marcas.html
- type: social_proof
- persuasion: Authority by association
- beat: trust
- blueprint_candidate: grid-card-assemble
- asset_candidates: assets/02-portfolio-0.png — real "Campañas Destacadas" screen with category filters; assets/03-collaborations-0.png — real 10-logo brand grid screen; assets/marca-la-casa-de-las-pupusas.png — client logo; assets/marca-kuskatan.png — client logo; assets/marca-guapollon.png — client logo; assets/marca-abel.png — client logo; assets/marca-barranko.png — client logo; assets/marca-vipros.png — client logo; assets/marca-sabor-del-cielo.png — client logo; assets/marca-la-casa-del-filete.png — client logo; assets/marca-la-pampa-centro-historico.png — client logo; assets/marca-emerino-realtor.png — client logo

narrativeRole: Prove they are real — named local brands already worked with them.
keyMessage: Restaurantes, hoteles y marcas reales ya trabajan con DREAMEZ.

- blueprint: grid-card-assemble (Adapt)
- focal: assets/03-collaborations-0.png
- roles: 02-portfolio-0 = supporting (real "Campañas Destacadas" screen as a framed card, opening beat); marca-*.png = cutout logos in the grid; 03-collaborations-0 = reference only (the grid is rebuilt from the real logo files so it can assemble)
- sfx: none

Adapt: keep the self-assembling tile grid as the signature; the opening shows the real portfolio screen first, then the grid assembles from the real client logos.
Scene 1 (0.0–1.6s): the real "Campañas Destacadas" screen enters as a framed card (inset ~8% margins, gold hairline border) rising from below with a long-tail settle; the label "PORTAFOLIO" sits above it.
Scene 2 (1.6–2.3s): the card scales down and fades back (scale-swap-transition) as the header "COLABORACIONES / Marcas con las que ha colaborado" assembles in the upper third, "colaborado" in Playfair italic gold; the sector line "RESTAURANTES · HOTELERÍA · REAL ESTATE · MARCAS" follows one beat later.
Scene 3 (2.3–4.6s): the gold thread draws the 4×3 grid rules (svg-path-draw), then the 10 logos pop into their cells one per half-beat in reading order (spring-pop-entrance, smooth settle, no overshoot), then the last two-cell slot reveals "+3 / 13 EN TOTAL" with a count-up 0→3.
Scene 4 (4.6–5.5s): hold the full wall; subtle jitter only.

## Frame 3 — Tres modos de trabajar

- scene: Four service words snap in on the beat, pure typography on black with a gold light sweep, then the three work modes stack as gold-hairline cards
- onscreen: "Video" / "Drone" / "Fotografía" / "Contenido digital" / "Tres modos de *trabajar*" / "Retrato de estudio" / "Editorial y campaña" / "Producto en negro"
- voiceover: ""
- duration: 6.5s
- poster: 5.5s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/03-servicios.html
- type: benefit_highlight
- persuasion: Value stacking
- beat: aspiration + confidence
- blueprint_candidate: kinetic-type-beats
- asset_candidates:

narrativeRole: Show the range — everything a brand needs under one roof.
keyMessage: Video, drone, foto y contenido, con un método claro.

- blueprint: kinetic-type-beats (Adapt)
- focal: (typography)
- roles: none — pure typography
- sfx: none

Adapt: keep the beat-by-beat word slam as the signature; the four services light up one per beat (gray → white), then the shot resolves into three stacked cards rather than a logo.
Scene 1 (0.0–2.4s): the four service words stand stacked in the upper third in dim gray (#2f2f2f-ish via text-secondary at low opacity); one per beat each flips to white with a short left→right gold light sweep across the word (kinetic-beat-slam on 0.0 / 0.57 / 1.14 / 1.71s), "Video" first.
Scene 2 (2.4–3.2s): the headline "Tres modos de trabajar" assembles below (per-word, "trabajar" in Playfair italic gold), the gold thread wipes under it.
Scene 3 (3.2–5.4s): the three mode cards rise in sequence one every ~0.7s (fromTo y + opacity, power3), each with its gold hairline border drawing on as it lands: "Retrato de estudio", "Editorial y campaña", "Producto en negro", each with its one-line description.
Scene 4 (5.4–6.5s): hold; the active card edge brightens on the third card only as it lands, then everything holds still.

## Frame 4 — El equipo

- scene: The real "El equipo DREAMEZ" screen; its three stats count up large in gold
- onscreen: "El equipo *DREAMEZ*" / "12+ años de experiencia" / "200+ proyectos completados" / "13 colaboraciones"
- voiceover: ""
- duration: 3.5s
- poster: 3s
- transition_in: crossfade
- status: animated
- src: compositions/frames/04-equipo.html
- type: social_proof
- persuasion: Statistical proof
- beat: trust + confidence
- blueprint_candidate: dataviz-countup
- asset_candidates: assets/06-about-0.png — real "El equipo DREAMEZ" screen with the 12+ / 200+ / 13 stats (no portraits)

narrativeRole: Close the credibility section with the site's own numbers.
keyMessage: Experiencia comprobada: 12+ años, 200+ proyectos.

- blueprint: dataviz-countup (Adapt)
- focal: (typography — the site's real numbers)
- roles: 06-about-0 = source of the numbers only, not shown (it contains the stock-portrait section context); no portraits
- sfx: none

Adapt: keep the count-up as the signature; three stats in a vertical stack instead of one exploding stat, values from the site.
Scene 1 (0.0–0.8s): label "SOBRE NOSOTROS" and headline "El equipo DREAMEZ" (DREAMEZ in Playfair italic gold) assemble in the upper third.
Scene 2 (0.8–2.8s): three stats reveal top to bottom on a 0.57s stagger, each a value-scaled counter (counting-dynamic-scale, mild scale growth) counting 0→12+, 0→200+, 0→13 in gold with its uppercase label fading in under it; a gold-dark hairline wipes in between each pair as the next stat starts.
Scene 3 (2.8–3.5s): hold the three numbers; still.

## Frame 5 — Trabajemos juntos (el formulario)

- scene: The site's real contact form, rebuilt 1:1 so it can move: fields fill in one by one, the "Video" chip lights gold, a tap on "ENVIAR SOLICITUD →"
- onscreen: "Tu proyecto empieza *aquí*" / "Nombre" / "Correo electrónico" / "Servicio: Video" / "ENVIAR SOLICITUD →"
- voiceover: ""
- duration: 6s
- poster: 5s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/05-formulario.html
- type: feature_showcase
- persuasion: Friction reduction
- beat: ease + control
- blueprint_candidate: device-surface-showcase
- asset_candidates: assets/07-contact-0.png — real "Trabajemos Juntos" form screen (layout reference for the rebuild); assets/07-contact-1.png — real bottom of form with the gold "ENVIAR SOLICITUD →" button; assets/form-filled.png — form crop with a typed email

narrativeRole: The hero beat — show how little it takes to start a project.
keyMessage: Llenar el formulario toma segundos.

- blueprint: device-surface-showcase (Adapt)
- focal: (rebuilt form — the real form's moving component)
- roles: 07-contact-0 / 07-contact-1 / form-filled = layout + styling reference for the 1:1 rebuild (labels, underline fields, chip pills, gold button); not shown as screenshots
- sfx: none

Adapt: keep the cursorless end-to-end loop completed inside the real surface; the surface is the site's own form rebuilt 1:1 because it must move.
Scene 1 (0.0–1.0s): label "CONTACTO" and headline "Tu proyecto empieza aquí" ("aquí" in Playfair italic gold) assemble in the upper third; the form fields' empty labels + gray underlines fade in below at the same time as a block (light, 0.3s after the headline).
Scene 2 (1.0–2.6s): the Nombre underline turns gold (the thread arrives here) and "María López" types in behind a gold caret (discrete-text-sequence); then the Correo underline turns gold and "maria@restaurante.com" types in.
Scene 3 (2.6–3.6s): the "SERVICIO DE INTERÉS" chips row; the "Video" chip fills gold with dark text on a beat (press-release-spring, smooth).
Scene 4 (3.6–5.2s): a white tap ring appears over the "ENVIAR SOLICITUD →" button, the button compresses and springs back (press-release-spring), the arrow nudges right, and the button label swaps to "ENVIADO ✓" on the next beat.
Scene 5 (5.2–6.0s): hold on the sent state; still.

## Frame 6 — La automatización trabaja

- scene: The submitted form shrinks into a node; a gold line runs Formulario → n8n → "Cliente guardado ✓" → "Correo enviado ✓", each step checking off
- onscreen: "Y en ese instante…" / "Formulario" / "n8n" / "Cliente guardado ✓" / "Correo de confirmación ✓" / "Automático. Sin esperas."
- voiceover: ""
- duration: 6s
- poster: 5.2s
- transition_in: crossfade
- status: animated
- src: compositions/frames/06-automatizacion.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: curiosity → relief
- blueprint_candidate: agent-progress-theater
- asset_candidates:

narrativeRole: Reveal what happens behind the button — the client is saved and answered automatically.
keyMessage: Tu solicitud queda registrada y confirmada al instante, sin intervención manual.

- blueprint: agent-progress-theater (Adapt)
- focal: (the four-node flow)
- roles: none — drawn nodes (abstract, labelled; no n8n UI)
- sfx: none

Adapt: keep trigger → working theater → checklist that checks off; the theater is a vertical node chain with a gold pulse.
Scene 1 (0.0–0.9s): headline "Y en ese instante…" ("instante…" in Playfair italic gold) assembles in the upper third; the first node "Formulario · Solicitud enviada" lands from a slight scale-down (it reads as the submitted button condensing into a node).
Scene 2 (0.9–2.4s): the gold connector draws downward from node 1 (svg-path-draw) and a small gold pulse dot travels it; node 2 "n8n · Automatización en marcha" lands as the pulse reaches it, its icon box showing "n8n".
Scene 3 (2.4–4.4s): the connector continues; node 3 "Cliente guardado" lands and its icon box fills gold with a ✓ drawing on; one beat later node 4 "Correo de confirmación · Enviado al cliente" lands and checks the same way.
Scene 4 (4.4–6.0s): "Automático. Sin esperas." ("Sin esperas." in Playfair italic gold) reveals under the chain; hold still.

## Frame 7 — El correo llega

- scene: A phone-style email notification drops in, then opens to a branded confirmation email
- onscreen: "DREAMEZ" / "Recibimos tu solicitud" / "Nos contactaremos contigo muy pronto." / "Respuesta al instante"
- voiceover: ""
- duration: 4.5s
- poster: 3.8s
- transition_in: push-slide UP
- status: animated
- src: compositions/frames/07-correo.html
- type: benefit_highlight
- persuasion: Risk reversal
- beat: peace of mind
- blueprint_candidate: titlecard-reveal
- asset_candidates: assets/logo-dreamez.png — white wordmark for the email header; assets/logo-monograma.png — DM monogram as the sender avatar

narrativeRole: Pay off the message from the client's side — they get proof they were heard.
keyMessage: El cliente recibe confirmación inmediata en su correo.

- blueprint: titlecard-reveal (Adapt)
- focal: (rebuilt email card)
- roles: logo-dreamez = email header wordmark; logo-monograma = notification avatar
- sfx: none

Adapt: keep the calm near-still card reveal as the signature; two cards (notification, email) instead of title cards, ending on the deliberate hold.
Scene 1 (0.0–0.9s): the phone-style notification (monogram avatar, "DREAMEZ · ahora", "Recibimos tu solicitud") drops in from above the upper third with a long-tail settle.
Scene 2 (0.9–2.4s): the email card unfolds beneath it (fromTo scaleY from the top edge + opacity): black header with the DREAMEZ wordmark and a gold rule, then "Hola María,", the headline "Recibimos tu solicitud" ("solicitud" in Playfair italic, gold-dark on the light card), the gold divider wiping in, the body line "Nos contactaremos contigo muy pronto para hablar de tu proyecto." and the sign-off.
Scene 3 (2.4–3.3s): "Respuesta al instante" ("instante" in Playfair italic gold) assembles under the card.
Scene 4 (3.3–4.5s): HELD FRAME — nothing moves; let it read.

## Frame 8 — Reserva tu sesión

- scene: The official DREAMEZ logo animation plays centered, then the CTA and URL settle under it
- onscreen: "Reserva tu *sesión*" / "dreamezsv.netlify.app"
- voiceover: ""
- duration: 5s
- poster: 4.5s
- transition_in: blur-crossfade
- status: animated
- src: compositions/frames/08-cta.html
- type: cta
- persuasion: Urgency-to-act
- beat: motivation
- blueprint_candidate: logo-assemble-lockup
- asset_candidates: assets/DREAMEZANIMATION.mp4 — [video] official 8s logo animation, monogram + wordmark on black (play muted, center-cropped); assets/logo-dreamez.png — white wordmark fallback

narrativeRole: Turn attention into the single action — go to the site and fill the form.
keyMessage: Entra a la web y reserva tu sesión.

- blueprint: logo-assemble-lockup (Adapt)
- focal: assets/DREAMEZANIMATION.mp4
- roles: DREAMEZANIMATION = [video] approved, muted, centered, scaled so the logo reads large, on a pure-black full-bleed ground; logo-dreamez = fallback only
- sfx: none

Adapt: the official logo animation IS the assemble; the push-through is replaced by the CTA settling under the resolved lockup.
Scene 1 (0.0–2.6s): pure-black ground; the official logo animation plays (monogram + DREAMEZ wordmark resolving), centered in the upper-middle band.
Scene 2 (2.6–3.6s): "Reserva tu sesión" ("sesión" in Playfair italic gold) rises in under the logo (per-word, power3).
Scene 3 (3.6–4.4s): the gold thread draws the URL pill outline (svg-path-draw around a rounded rect) and "dreamezsv.netlify.app" fades in inside it in #E8C97A.
Scene 4 (4.4–5.0s): final frame — hold, then a short fade of the CTA group to black over the last ~0.3s (the only exit in the film).
