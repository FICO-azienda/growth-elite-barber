# Growth Elite Barber Milano · sito demo (FICO)

Sito vetrina statico (HTML + CSS + JS vanilla, nessuna dipendenza né build). Unica risorsa esterna: i font Anton e Archivo da Google Fonts. Ispirazione di layout: crispmtl.com (titoli enormi in maiuscolo, foto a tutta pagina, menu a schermo intero, "Prenota" sempre visibile).

## Avvio in locale

```bash
cd growth-elite-barber
python3 -m http.server 4326
```

Poi apri http://localhost:4326. Si può pubblicare così com'è su GitHub Pages, Vercel o Netlify.

## Struttura

- `index.html`: pagina unica con Hero, nastro dei tagli, L'idea, Servizi, Lookbook (tagli da Instagram), Il salone (galleria + lightbox), Recensioni, Prenota dall'app, Orari e contatti, Footer
- `css/style.css`: stili e responsive (blu elettrico `#0000ff` del logo + bianco)
- `js/main.js`: header che diventa bianco allo scroll, menu a schermo intero, stato "aperto ora" (ora di Milano), mappa caricata solo su clic, lightbox, barra rapida mobile che apre lo store giusto (iOS/Android), animazioni di comparsa (disattivate con prefers-reduced-motion)
- `images/`: foto in JPG/WebP, logo del salone (PNG trasparente blu e bianco), logo FICO

## Fonti (verificate il 20/10/2026)

1. Linktree: https://linktr.ee/growthelitebarber
2. Scheda Google Maps "Growth Elite Barber Milano"
3. Instagram: https://www.instagram.com/growthelitebarber/
4. Pagina App Store dell'app "GROWTH - BARBER" (collegata dal Linktree)

### Dati verificati

- Indirizzo: Via Piero della Francesca 16, 20154 Milano (Maps e bio Instagram)
- Telefono: 02 9144 4123 (Maps)
- Email: growthelitebarber@gmail.com (Linktree)
- Orari (Maps): Lun–Ven 10–20 · Sab 8:30–18:30 · Dom chiuso
- Valutazione Google: 4,9 su 237 recensioni (dato che cambia nel tempo)
- Prenotazione: app GROWTH - BARBER, App Store id6470934965 e Google Play `app.growth.working` (Linktree). Le funzioni elencate nella sezione Prenota vengono dalla descrizione ufficiale su App Store
- Bio Instagram: "Da un'idea di @elprimero23", "We speak ENGLISH & ESPAÑOL". TikTok collegato: @elprimero23
- Nomi del team citati nelle recensioni Google: Alessandro, Titti, Daniel, William
- Servizi: tag "Servizi" indicati dai clienti nelle recensioni Google (taglio sfumato, personalizzato, con forbici, capelli ricci, shampoo e balsamo, trattamento del cuoio capelluto, cura/rasatura barba, rasatura con asciugamano caldo, rifinitura sopracciglia, manicure per uomo, tagli per bambini) + "Haircut & beard trim" da Instagram
- Fascia di spesa 20–40 €: indicata dai clienti nelle recensioni Google ("20-25 €", "35-40 €")
- Nomi e descrizioni dei tagli nel Lookbook: didascalie dei post Instagram (middle part, warrior cut, taper fade, buzzcut, taper fade riccio, haircut & beard trim, barba, "X Alvaro Morata")
- Citazioni nella sezione Recensioni: estratti di recensioni pubbliche su Google

### Foto

- Interni, vetrina e specchi: galleria foto della scheda Google Maps
- Lookbook e "Weekend di formazione": copertine dei post Instagram (max 360×640 senza login)
- Logo: immagine profilo del Linktree (sfondo bianco reso trasparente; variante bianca derivata)

### Da confermare con il titolare

- Listino prezzi ufficiale (non pubblico: è solo nell'app). Sul sito c'è solo la fascia indicata dai clienti
- Ruoli del team e se si vogliono i nomi/foto dei barbieri sul sito
- Uso del post con Alvaro Morata e delle foto dei clienti
- Foto in alta risoluzione per il Lookbook (quelle Instagram sono a 360 px di larghezza)
