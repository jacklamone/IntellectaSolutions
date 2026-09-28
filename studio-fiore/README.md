# Studio Dott. Stefano Fiore — sito web

Sito del cliente **Studio Dott. Stefano Fiore** (Sassari), consulenze aziendali e
finanza agevolata. Realizzato da Intellecta Solutions.

La cartella è **autonoma**: HTML/CSS/JS statici, font e immagini in locale, link
relativi. Si può spostare così com'è su un proprio repository o sito Netlify
(publish directory = questa cartella, nessun build command).

## Pagine

| File | Contenuto |
|------|-----------|
| `index.html` | Home: hero, lo Studio, servizi, metodo, valori, intervista, CTA |
| `chi-siamo.html` | Lo Studio, profilo del Dott. Fiore, come si svolge la consulenza, in cosa crediamo |
| `cosa-facciamo.html` | Finanza agevolata (+ elenco in 9 punti), microcredito, certificazioni, formazione, metodo |
| `storie-di-successo.html` | 4 casi reali in forma anonima, con la cifra ottenuta in evidenza |
| `contatti.html` | Recapiti + form Netlify `contatti-studio-fiore` |
| `note-legali.html`, `privacy.html`, `cookie.html` | Note legali, privacy policy e cookie policy con i dati del titolare |
| `grazie.html` | Conferma invio del form senza JavaScript |

Header e footer sono ripetuti in ogni pagina: una modifica al menu o ai
recapiti va fatta in **tutti** i file `.html`.

## Stato dei contenuti

Dati ricevuti dal Dott. Fiore il 27/09/2026 (PDF compilato) e già inseriti:
recapiti, orari, WhatsApp, P.IVA, C.F., PEC, denominazione, conservazione 12 mesi,
profilo biografico corretto, nuovo testo di "Cosa ci distingue", Facebook, 4 storie di successo.

Ancora da fare:

- [ ] Dominio definitivo (non indicato): collegarlo, poi rimuovere `<meta name="robots" content="noindex, nofollow">` da tutte le pagine e aggiungere `canonical` e sitemap
- [ ] Netlify → Forms → notifiche: inviare le richieste del modulo a fiorestefano@hotmail.com
- [ ] Instagram: nessun profilo indicato, icona rimossa (aggiungerla se verrà creato)
- [ ] Far rileggere privacy e note legali a un consulente legale
- Nessuna foto del Dott. Fiore per scelta: il sito punta su serietà e metodo, non sul volto

## Note tecniche

- Font: Fraunces (titoli) e Manrope (testi), auto-ospitati in `assets/fonts/`.
- Logo: `logo.webp` per fondi chiari, `logo-light.webp` (contorno chiaro) per fondi scuri.
- Video intervista: YouTube in modalità `youtube-nocookie`, caricato solo al clic.
- Animazioni disattivate con "riduci movimento" del sistema operativo.
