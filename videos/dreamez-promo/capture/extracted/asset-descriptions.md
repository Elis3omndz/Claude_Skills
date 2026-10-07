# DREAMEZ — asset inventory

Brand: DREAMEZ, producción audiovisual en El Salvador y Guatemala — video, drone,
fotografía y contenido digital para restaurantes, hotelería, real estate y marcas.
Tagline: "Captura la realidad". Palette black #0A0A0A + gold #C9A84C / #E8C97A.

The site was served locally from the Dreamez repo (the public domain is blocked in
this session). `hyperframes capture` could not render it (React runtime + intro
preloader), so the screens below were shot with Playwright at a 432x768 mobile
viewport, 2.5x → exactly 1080x1920.

## Captured screens (capture/mobile/, 1080x1920)

- mobile/00-hero.png — Hero: "CAPTURA LA REALIDAD", "VIDEO · DRONE · FOTOGRAFÍA · CONTENIDO DIGITAL", gold "EXPLORAR PORTAFOLIO ↓" button over a dark mountain photo. Strong hook plate.
- mobile/02-portfolio-0.png — "PORTAFOLIO / Campañas Destacadas" heading, category filters (Todos · Restaurantes · Hoteles y Airbnb), first campaign cards (DC, Abel Nogales). Card thumbnails are empty (videos not in repo).
- mobile/02-portfolio-1.png — More campaign cards with play buttons: Percepción de Venta, Don Bigote, Beraká, Abel Cipreses. Thumbnails empty.
- mobile/02-portfolio-2.png — "VER 5 PIEZAS MÁS", "Mostrando 8 de 13 piezas" and the start of "Marcas con las que ha colaborado".
- mobile/03-collaborations-0.png — "COLABORACIONES / Marcas con las que ha colaborado": grid of 10 round brand logos. Best social-proof plate.
- mobile/03-collaborations-1.png — Same section scrolled; "Galería de Imágenes" heading + category filters (images empty: Unsplash blocked).
- mobile/05-galeria-0.png — "NUESTRO TRABAJO / Galería de Imágenes" heading + filters (Comercial, Gastronomía, Retrato, Real Estate, Eventos, Artística). Images empty — use heading only.
- mobile/06-about-0.png — "SOBRE NOSOTROS / El equipo DREAMEZ", intro copy, stats 12+ años de experiencia · 200+ proyectos completados · 13 colaboraciones.
- mobile/06-about-1.png — Team cards with B&W portraits: Diego Méndez (Dirección & cámara), Valeria Cruz (Producción), Marco Alvarado (Drone & aéreas), Andrea Rivas (Fotografía fija).
- mobile/06-about-2.png — Team card: Sergio Peña (Postproducción & color).
- mobile/07-contact-0.png — "CONTACTO / Trabajemos Juntos" form: Nombre, Correo electrónico, WhatsApp / Teléfono, Fecha aproximada, Servicio de interés chips (Video, Fotografía, Drone, Contenido digital, Otro). Key plate for the form beat.
- mobile/07-contact-1.png — Bottom of form: "Cuéntanos brevemente sobre tu proyecto", gold "ENVIAR SOLICITUD →", WhatsApp line, footer.
- mobile/form-empty.png / form-filled.png — Form element crops (filled shows "maria@restaurante.com"). Reference for the rebuilt animated form.

## Brand media (capture/assets/)

- assets/videos/DREAMEZANIMATION.mp4 — 8s 1920x1080 official logo animation: metallic "DM" monogram + "DREAMEZ" wordmark resolving on black, has audio. Best for the closing sting (center-crop to 9:16 works: logo is centered).
- assets/img/logo-dreamez.png — white DREAMEZ wordmark logo, transparent, 605x207.
- assets/img/logo-monograma.png — white DM monogram, transparent, 128x96.
- assets/img/marca-*.png — 10 client logos: Abel, Barranko, Emerino Realtor, Guapollón, Kuskatán, La Casa de las Pupusas, La Casa del Filete, La Pampa Centro Histórico, Sabor del Cielo, Vipros.
- assets/img/hero-1.jpg — snowy peaks above a sea of clouds at sunset, 1920x1280.
- assets/img/hero-2.jpg — misty green mountain valley with a lone figure, 1920x1275.
- assets/img/hero-3.jpg — green cliffs and clouds at golden hour, 1920x1144.
- assets/img/hero-4.jpg — footbridge into a dense forest, 1920x1280.
- assets/img/fotografia-flash.jpg — confetti burst over a concert crowd, blue/purple light, 1920x1281. Used by the site's "La luz decide" section.
- assets/img/serie-p1.jpg — photographer holding a camera toward the lens in an autumn forest (landscape).
- assets/img/serie-p3.jpg — bright modern kitchen with bar stools (portrait).
- assets/img/serie-p4.jpg — neutral-tone clothing rack with pampas grass (landscape).
- assets/img/serie-p5.jpg — fashion flat lay: sneakers, sunglasses, bag, scarf (portrait).
- assets/img/serie-p6.jpg — two latte-art coffees on wood among plants (portrait).
- assets/img/serie-p10.jpg — green cliffs at sunset (landscape).
- assets/img/serie-p11.jpg — smiling man portrait, white tee (portrait).
- assets/img/serie-p12.jpg — modern office corridor (landscape).
- assets/img/serie-p13.jpg — white modern villa with pool (landscape).
- assets/img/serie-p14.jpg — event hall set up with round tables and screens (landscape).
- assets/img/serie-p15.jpg — resort pool deck with loungers and thatched building (landscape).
- assets/img/serie-p16.jpg — same confetti concert image as fotografia-flash (landscape).
- assets/img/serie-p7.jpg, serie-p8.jpg, serie-p9.jpg — duplicates of hero-1, hero-2, hero-4 at 800px.
- assets/img/equipo-*.jpg — source portraits of the five team members (shown in B&W on the site).
- assets/fonts/ — Montserrat (latin), Playfair Display 700 and italic (latin) woff2.

## Excluded

- serie-p2.jpg / 97e38b16.jpg — Netflix logo render: third-party trademark, never use.
- Campaign videos and thumbnails (Videos/…) — not in the repo.
- Gallery images — hotlinked from Unsplash, blocked here.
