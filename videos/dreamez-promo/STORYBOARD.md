---
format: 1080x1920
duration: 40s
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

## Frame 1 — Gancho

- scene: The phone flips in from the bottom showing the real hero "CAPTURA LA REALIDAD"; big words slam around it
- voiceover: "¿Quieres que tu marca se vea increíble en redes?"
- duration: 3.5s
- transition_in: cut
- status: built
- src: compositions/frames/01-gancho.html
- type: hook
- persuasion: Direct address
- beat: curiosity + aspiration
- blueprint: kinetic-type-beats
- asset_candidates: assets/00-hero.png — real mobile hero screen "CAPTURA LA REALIDAD" (phone screen)

narrativeRole: Stop the scroll with a direct question to the business owner.
keyMessage: Tu marca puede verse increíble.

## Frame 2 — La marca

- scene: The DREAMEZ logo pops out of the phone screen; three service chips (Video · Drone · Fotografía) orbit out on the beat
- voiceover: "Conoce Drímez: video, drone y fotografía que capturan lo mejor de tu negocio."
- duration: 5s
- transition_in: zoom-through
- status: built
- src: compositions/frames/02-dreamez.html
- type: product_intro
- persuasion: Value stacking
- beat: excitement
- blueprint: kinetic-type-beats
- asset_candidates: assets/00-hero.png — real hero screen (phone screen); assets/logo-dreamez.png — white DREAMEZ wordmark that pops out

narrativeRole: Name the brand and its three services with energy.
keyMessage: DREAMEZ hace video, drone y fotografía.

## Frame 3 — Clientes

- scene: A 3D laptop scrolls the real desktop site (hero → Campañas Destacadas → Marcas); the client logos fly out of the screen and land around it
- voiceover: "Restaurantes, hoteles y marcas ya confían en nosotros."
- duration: 4.5s
- transition_in: push-slide LEFT
- status: built
- src: compositions/frames/03-marcas.html
- type: social_proof
- persuasion: Authority by association
- beat: trust
- blueprint: device-surface-showcase
- asset_candidates: assets/desktop-scroll.png — real desktop site from hero to the brands wall (laptop screen, scrolls); assets/marca-la-casa-de-las-pupusas.png — client logo; assets/marca-kuskatan.png — client logo; assets/marca-guapollon.png — client logo; assets/marca-abel.png — client logo; assets/marca-barranko.png — client logo; assets/marca-vipros.png — client logo; assets/marca-sabor-del-cielo.png — client logo; assets/marca-la-casa-del-filete.png — client logo

narrativeRole: Proof — real local brands already work with them.
keyMessage: Marcas reales ya confían en DREAMEZ.

## Frame 4 — Cifras

- scene: Giant gold counters 12+ and 200+ bounce in and count up, with the site's own stat labels
- voiceover: "Más de doce años de experiencia y más de doscientos proyectos."
- duration: 4s
- transition_in: zoom-through
- status: built
- src: compositions/frames/04-cifras.html
- type: social_proof
- persuasion: Statistical proof
- beat: confidence
- blueprint: dataviz-countup
- asset_candidates:

narrativeRole: Close the credibility section with the site's numbers.
keyMessage: 12+ años, 200+ proyectos.

## Frame 5 — El formulario

- scene: The phone returns showing the real "Trabajemos Juntos" form; fields fill themselves, "Video" turns gold, a finger taps ENVIAR SOLICITUD; a "¡en segundos!" sticker pops
- voiceover: "¿Y lo mejor? Reservas tu sesión desde nuestra web en segundos: llenas un formulario cortito y tocas enviar."
- duration: 7s
- transition_in: zoom-through
- status: built
- src: compositions/frames/05-formulario.html
- type: feature_showcase
- persuasion: Friction reduction
- beat: ease
- blueprint: device-surface-showcase
- asset_candidates: assets/07-contact-0.png — real form screen (styling reference for the 1:1 in-phone rebuild)

narrativeRole: The hero beat — how little it takes to book.
keyMessage: Reservar toma segundos.

## Frame 6 — La confirmación

- scene: An envelope/email card flies out of the phone and opens: "¡Recibimos tu solicitud!"; a gold check bursts with sparkles; "¡Al instante!" slams in
- voiceover: "Y al instante te llega la confirmación a tu correo. ¡Así de fácil, sin esperas!"
- duration: 6s
- transition_in: crossfade
- status: built
- src: compositions/frames/06-confirmacion.html
- type: benefit_highlight
- persuasion: Risk reversal
- beat: delight + peace of mind
- blueprint: titlecard-reveal
- asset_candidates: assets/logo-dreamez.png — wordmark for the email header; assets/logo-monograma.png — sender avatar

narrativeRole: Pay off the promise from the client's side.
keyMessage: Confirmación inmediata, sin esperar.

## Frame 7 — Reserva tu sesión

- scene: The official DREAMEZ logo animation; "Reserva tu sesión" and the URL pill pop in
- voiceover: "Reserva tu sesión hoy. Drímez: captura la realidad."
- duration: 5s
- transition_in: blur-crossfade
- status: built
- src: compositions/frames/07-cta.html
- type: cta
- persuasion: Urgency-to-act
- beat: motivation
- blueprint: logo-assemble-lockup
- asset_candidates: assets/DREAMEZANIMATION.mp4 — [video] official logo animation (muted, centered); assets/logo-dreamez.png — fallback

narrativeRole: One action: go book.
keyMessage: Reserva hoy en la web.
