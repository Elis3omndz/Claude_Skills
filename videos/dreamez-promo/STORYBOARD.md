---
format: 1080x1920
duration: 34s
message: "Con DREAMEZ tu marca se ve increíble, y reservar tu sesión toma segundos."
arc: Gancho → La marca → Clientes → Cifras → Demo del formulario (llenar → confirmación al instante) → CTA
audience: Dueños de negocios en El Salvador y Guatemala (restaurantes, hoteles, real estate, marcas)
mode: collaborative
music: none
language: es
---

# DREAMEZ — Reel v2 (9:16, ~38–42s, con narradora)

Narrated by Dora (Kokoro `ef_dora`, Spanish) from `SCRIPT.md`; no baked music (the user adds
a trending audio in Instagram). Visible text is short: hero words, numbers, UI — the voice
carries the sentences.

## Decisions (v2)

- **Concept — floating devices:** the REAL site (captured screens) lives inside a 3D phone
  and a 3D laptop floating over the black/gold ground; real site elements (client logos, the
  DREAMEZ logo, the form, the confirmation email) **pop out of the screen** toward the viewer.
  Interpretation of the user's Pinterest reference (not reachable here), confirmed by the user.
- **Tone:** animated, fun, eye-catching. Playful overshoot is explicitly allowed on pop-outs
  and word slams only (user asked for "divertido"); everything else settles smooth.
- **Spine:** the same phone is the hero prop — it opens the film, returns for the form,
  and the email flies out of it. The laptop appears once (the clients beat).
- **Language:** no technical terms; never "n8n", "automatización", "webhook". Say the benefit.
- **Brand:** frame.md — ground #0A0A0A, gold #C9A84C / #E8C97A / #9A7A32, Montserrat 800 +
  one Playfair italic gold word. Device bodies are dark graphite with a thin gold rim.
- **Bans:** no stock photos/portraits (gallery images, team portraits); no n8n UI; no
  purple/blue gradients; nothing in the Reels keep-out (top 220px, bottom 380px) except
  device bodies passing through.
- **Truthfulness:** phone/laptop screens show real captures of dreamezsv.netlify.app (served
  from the user's repo). The form is rebuilt 1:1 so it can be filled; the confirmation email is
  a depiction of the flow the user is connecting — it must be live before publishing.

## Video direction

- **Ground:** #0A0A0A with a soft warm radial pool (#1a1712 center) behind the device; Frame 7 on pure #000 for the logo clip.
- **Devices:** graphite phone (radius 70px, 16px bezel, 3px gold rim #9A7A32, notch) and laptop (gold rim, graphite base). Their screens show the REAL captures untouched; only typed form values, the selected chip and the sent state are overlaid on the real fields.
- **Motion grammar:** devices fly in with 3D tilt and settle on power3/expo; pop-outs and stickers use a playful back.out overshoot (explicit user ask: "divertido"); every reveal lands on the narrator's word (cues in `.hyperframes/word-cues.json`).
- **Holds:** frame 6 holds ~0.8s after "¡Así de fácil!"; frame 7 holds the lockup.
- **Negative list:** no stock photos/portraits, no technical words on screen, no purple/blue gradients, no endless loops, nothing important outside y 220–1540.

## Frame 1 — Gancho

- scene: The phone flips in from the bottom showing the real hero "CAPTURA LA REALIDAD"; big words slam around it
- voiceover: "¿Quieres que tu marca se vea increíble en redes?"
- duration: 3.267s
- transition_in: cut
- status: animated
- src: compositions/frames/01-gancho.html
- type: hook
- persuasion: Direct address
- beat: curiosity + aspiration
- blueprint: kinetic-type-beats
- asset_candidates: assets/phone-hero.png — real mobile hero screen "CAPTURA LA REALIDAD" at phone proportions (phone screen)

narrativeRole: Stop the scroll with a direct question to the business owner.
keyMessage: Tu marca puede verse increíble.

- focal: assets/phone-hero.png
- roles: phone-hero = phone screen
Scene 1 (0.0–0.9s): the phone flies up from below the frame tumbling in 3D and settles tilted, centered low; "¿Tu marca se ve" assembles word by word in the upper third on "¿Quieres…".
Scene 2 (1.6–2.2s): on "increíble" the gold sticker "¡INCREÍBLE!" slams down from scale 2 with a playful overshoot and a small rotation.
Scene 3 (2.3–3.27s): "en redes?" pops in under it ("redes?" Playfair italic gold); hold.

## Frame 2 — La marca

- scene: The DREAMEZ logo pops out of the phone screen; three service chips (Video · Drone · Fotografía) orbit out on the beat
- voiceover: "Conoce Drímez: video, drone y fotografía que capturan lo mejor de tu negocio."
- duration: 5.123s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/02-dreamez.html
- type: product_intro
- persuasion: Value stacking
- beat: excitement
- blueprint: kinetic-type-beats
- asset_candidates: assets/phone-hero.png — real hero screen (phone screen); assets/logo-dreamez.png — white DREAMEZ wordmark that pops out

narrativeRole: Name the brand and its three services with energy.
keyMessage: DREAMEZ hace video, drone y fotografía.

- focal: assets/logo-dreamez.png
- roles: phone-hero = phone screen; logo-dreamez = pop-out hero
Scene 1 (0.0–0.5s): the phone sits lower-center, tilted the other way.
Scene 2 (0.45–1.2s): on "Drímez" the DREAMEZ logo shoots out of the phone screen, grows and lands in the upper third.
Scene 3 (1.0–2.3s): the gold pills VIDEO, DRONE, FOTOGRAFÍA spring out from behind the phone one per spoken word and land around it.
Scene 4 (2.7–5.1s): the phone turns gently toward camera on "capturan lo mejor de tu negocio"; hold.

## Frame 3 — Clientes

- scene: A 3D laptop scrolls the real desktop site (hero → Campañas Destacadas → Marcas); the client logos fly out of the screen and land around it
- voiceover: "Restaurantes, hoteles y marcas ya confían en nosotros."
- duration: 4.042s
- transition_in: push-slide LEFT
- status: animated
- src: compositions/frames/03-marcas.html
- type: social_proof
- persuasion: Authority by association
- beat: trust
- blueprint: device-surface-showcase
- asset_candidates: assets/desktop-scroll.png — real desktop site from hero to the brands wall (laptop screen, scrolls); assets/marca-la-casa-de-las-pupusas.png — client logo; assets/marca-kuskatan.png — client logo; assets/marca-guapollon.png — client logo; assets/marca-abel.png — client logo; assets/marca-barranko.png — client logo; assets/marca-vipros.png — client logo; assets/marca-sabor-del-cielo.png — client logo; assets/marca-la-casa-del-filete.png — client logo

narrativeRole: Proof — real local brands already work with them.
keyMessage: Marcas reales ya confían en DREAMEZ.

- focal: assets/desktop-scroll.png
- roles: desktop-scroll = laptop screen (scrolls); marca-* = pop-out logos
Scene 1 (0.0–0.5s): the laptop slides in from the right in 3D and settles.
Scene 2 (0.2–2.3s): the real desktop site scrolls inside the laptop from the hero through Campañas Destacadas down to the brands wall.
Scene 3 (1.9–3.3s): the client logos fly out of the screen one after another and land above and below the laptop with a playful pop; "Ya confían en nosotros" lands at the top on "confían".
Scene 4 (3.3–4.0s): hold.

## Frame 4 — Cifras

- scene: Giant gold counters 12+ and 200+ bounce in and count up, with the site's own stat labels
- voiceover: "Más de doce años de experiencia y más de doscientos proyectos."
- duration: 4.113s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/04-cifras.html
- type: social_proof
- persuasion: Statistical proof
- beat: confidence
- blueprint: dataviz-countup
- asset_candidates:

narrativeRole: Close the credibility section with the site's numbers.
keyMessage: 12+ años, 200+ proyectos.

- focal: (numbers)
Scene 1 (0.35–1.3s): "12+" slams in (gold, huge) and counts 0→12 on "doce"; the white sticker "AÑOS DE EXPERIENCIA" drops in on "experiencia".
Scene 2 (2.1–3.1s): "200+" slams in and counts 0→200 on "doscientos"; the gold sticker "PROYECTOS" drops on "proyectos".
Scene 3 (3.1–4.1s): hold.

## Frame 5 — El formulario

- scene: The phone returns showing the real "Trabajemos Juntos" form; fields fill themselves, "Video" turns gold, a finger taps ENVIAR SOLICITUD; a "¡en segundos!" sticker pops
- voiceover: "¿Y lo mejor? Reservas tu sesión desde nuestra web en segundos: llenas un formulario cortito y tocas enviar."
- duration: 6.951s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/05-formulario.html
- type: feature_showcase
- persuasion: Friction reduction
- beat: ease
- blueprint: device-surface-showcase
- asset_candidates: assets/phone-form.png — real "Trabajemos Juntos" form section, tall capture (phone screen, scrolls; typed values overlaid on the real fields)

narrativeRole: The hero beat — how little it takes to book.
keyMessage: Reservar toma segundos.

- focal: assets/phone-form.png
- roles: phone-form = phone screen (real form; scrolls; overlays only on real fields)
Scene 1 (0.0–0.8s): the phone flies in large and centered with the real "Trabajemos Juntos" form on screen.
Scene 2 (3.0–3.6s): on "segundos" the sticker "¡EN SEGUNDOS!" slams top-right over the phone.
Scene 3 (3.75–4.95s): on "llenas un formulario" the Nombre and Correo fields fill with "María López" and "maria@restaurante.com" (gold underline, caret).
Scene 4 (4.95–5.5s): the screen scrolls to the button and the "VIDEO" chip turns gold.
Scene 5 (5.45–6.95s): a white tap ring presses ENVIAR SOLICITUD on "tocas enviar"; the button flips to "¡ENVIADO!" with a check; hold.

## Frame 6 — La confirmación

- scene: An envelope/email card flies out of the phone and opens: "¡Recibimos tu solicitud!"; a gold check bursts with sparkles; "¡Al instante!" slams in
- voiceover: "Y al instante te llega la confirmación a tu correo. ¡Así de fácil, sin esperas!"
- duration: 5.458s
- transition_in: crossfade
- status: animated
- src: compositions/frames/06-confirmacion.html
- type: benefit_highlight
- persuasion: Risk reversal
- beat: delight + peace of mind
- blueprint: titlecard-reveal
- asset_candidates: assets/phone-form.png — real form (small phone, sent state); assets/logo-dreamez.png — wordmark for the email header; assets/logo-monograma.png — sender avatar

narrativeRole: Pay off the promise from the client's side.
keyMessage: Confirmación inmediata, sin esperar.

- focal: (email card)
- roles: phone-form = small phone screen; logo-dreamez = email header; logo-monograma = notification avatar
Scene 1 (0.0–0.9s): the small phone sits bottom-left tilted; "¡Al instante!" slams in at the top on "instante".
Scene 2 (1.2–2.3s): on "confirmación" an email card flies out of the phone, spins upright and opens in the center.
Scene 3 (2.4–2.9s): on "correo" a gold check badge pops on the card's corner and a burst of gold sparkles fires outward.
Scene 4 (3.0–4.4s): "¡Así de fácil!" sticker drops below the card on "Así", "SIN ESPERAS" pill on "esperas"; hold.

## Frame 7 — Reserva tu sesión

- scene: The official DREAMEZ logo animation; "Reserva tu sesión" and the URL pill pop in
- voiceover: "Reserva tu sesión hoy. Drímez: captura la realidad."
- duration: 5.515s
- transition_in: blur-crossfade
- status: animated
- src: compositions/frames/07-cta.html
- type: cta
- persuasion: Urgency-to-act
- beat: motivation
- blueprint: logo-assemble-lockup
- asset_candidates: assets/DREAMEZANIMATION.mp4 — [video] official logo animation (muted, centered); assets/logo-dreamez.png — fallback

narrativeRole: One action: go book.
keyMessage: Reserva hoy en la web.

- focal: assets/DREAMEZANIMATION.mp4
- roles: DREAMEZANIMATION = [video] approved, muted, x=90 y=360 w=900 h=506
Scene 1 (0.0–3.0s): the official logo animation plays on black.
Scene 2 (0.5–1.6s): "Reserva tu sesión" pops in under the logo on the narrator's words; the gold URL pill bounces in on "hoy".
Scene 3 (2.4–3.3s): "CAPTURA LA REALIDAD" spaces out in gold under the pill on "captura la realidad".
Scene 4 (3.3–5.5s): hold; the CTA fades out over the last 0.3s.
