# Wireframe — Home Page
**Love Sun — Beauty Center**
**Versione:** 1.0
**Data:** Giugno 2026
**Priorità:** Alta (pagina 1/16)

---

## Scopo della pagina

| | |
|--|--|
| **Obiettivo business** | Far comprendere immediatamente chi è Love Sun, cosa offre e generare conversioni (prenotazioni, WhatsApp, consulenze) |
| **Obiettivo utente** | Capire se Love Sun è il posto giusto per me e come prenotare |
| **Conversione primaria** | Prenotazione online (Treatwell) o chiamata |
| **Conversione secondaria** | Richiesta consulenza gratuita via WhatsApp |

---

## Layout — Ordine delle Sezioni

```
HEADER (sticky)
↓
HERO
↓
TRUST BAR
↓
SERVIZI PRINCIPALI
↓
PERCHÉ SCEGLIERCI
↓
OFFERTE DEL MESE
↓
RECENSIONI
↓
SEDI
↓
CTA FINALE
↓
FOOTER
```

---

## Componenti Dettagliati

---

### HEADER (sticky — sempre visibile)

**Posizione:** Fixed top, visibile durante lo scroll

**Contenuto sinistra:**
- Logo Love Sun

**Contenuto centro:**
- Menu navigazione:
  `Servizi` | `Offerte` | `Le nostre Sedi` | `Chi Siamo` | `Contatti`
  - Servizi: dropdown con Epilazione Laser / Trattamenti Corpo & T-Shape / Solarium / Nail Center / Cerette / Pedicure / Pulizia Viso / Massaggi

**Contenuto destra:**
- [ 📞 Chiama ] — link tel
- [ 💬 WhatsApp ] — link wa.me
- [ Prenota Ora ] — CTA primaria, bottone evidenziato

**Note UX:**
- Su mobile: logo sinistra + hamburger destra + icona WhatsApp sempre visibile
- Il bottone "Prenota Ora" deve rimanere visibile in tutte le condizioni
- Header diventa leggermente opaco su scroll per mantenere leggibilità

---

### SEZIONE 1 — HERO

**Obiettivo:** Comunicare in 3 secondi chi siamo, cosa facciamo e cosa fare adesso.

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   [IMMAGINE EMOZIONALE — full width, donna trattamento] │
│                                                         │
│   ┌─────────────────────────────────────────────────┐   │
│   │                                                 │   │
│   │  H1:                                            │   │
│   │  Bellezza, benessere e risultati concreti.      │   │
│   │  Nel tuo centro estetico di fiducia.            │   │
│   │                                                 │   │
│   │  H2:                                            │   │
│   │  Tecnologie avanzate, professionisti            │   │
│   │  qualificati e percorsi personalizzati          │   │
│   │  per prenderti cura di te.                      │   │
│   │  Due centri in Lombardia: Bregnano e Carugate.  │   │
│   │                                                 │   │
│   │  [ Prenota Ora ]  [ Consulenza Gratuita ]       │   │
│   │                                                 │   │
│   └─────────────────────────────────────────────────┘   │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

**H1:** Bellezza, benessere e risultati concreti. Nel tuo centro estetico di fiducia.

**H2:** Tecnologie avanzate, professionisti qualificati e percorsi personalizzati per prenderti cura di te. Due centri in Lombardia: Bregnano e Carugate.

**CTA Primaria:** `Prenota Ora` → link Treatwell

**CTA Secondaria:** `Consulenza Gratuita` → ancoraggio a sezione sedi / form WhatsApp

**Componenti:**
- Immagine hero full-width emozionale (donna in trattamento, atmosfera professionale e accogliente)
- Overlay testo su lato sinistro/centro
- Due CTA affiancate, nettamente distinte per gerarchia visiva
- Badge di fiducia opzionale sotto le CTA: "⭐ 4,9/5 su Treatwell · 419 recensioni"

**Note UX:**
- L'H1 deve essere leggibile anche su mobile senza scroll
- La CTA "Prenota Ora" deve essere la più visibile
- Evitare slider/carosello — immagine statica aumenta le conversioni
- Su mobile: immagine in alto, testo + CTA sotto

---

### SEZIONE 2 — TRUST BAR

**Obiettivo:** Stabilire fiducia immediatamente dopo il primo impatto visivo.

```
┌───────────────────────────────────────────────────────────────────┐
│                                                                   │
│  ⭐ 4,9/5          🏆 FDA           👥 Team            📍 2 Sedi   │
│  419 recensioni    Approved        Qualificato         Lombardia  │
│  su Treatwell      T-Shape 2       Specializzato       Como · MI  │
│                                                                   │
└───────────────────────────────────────────────────────────────────┘
```

**4 badge affiancati:**

1. **⭐ 4,9/5 su Treatwell** — 419 recensioni verificate
2. **🏆 FDA Approved** — T-Shape 2 certificato FDA
3. **👥 Team Specializzato** — Professioniste qualificate
4. **📍 2 Sedi in Lombardia** — Bregnano (CO) · Carugate (MI)

**Note UX:**
- Sfondo neutro/chiaro, icone semplici
- Testo piccolo ma leggibile
- Su mobile: 2 badge per riga (griglia 2×2)
- Non linkare — la trust bar informa, non naviga

---

### SEZIONE 3 — SERVIZI PRINCIPALI

**Obiettivo:** Mostrare l'ampiezza dell'offerta e indirizzare l'utente al servizio di interesse.

**H2:** I nostri trattamenti

**H3 (sottotitolo):** Dall'epilazione definitiva al rimodellamento corpo, dal solarium professionale al nail center: tutto quello di cui hai bisogno, in un unico posto.

```
┌──────────────────┐ ┌──────────────────┐ ┌──────────────────┐ ┌──────────────────┐
│                  │ │                  │ │                  │ │                  │
│  [IMMAGINE]      │ │  [IMMAGINE]      │ │  [IMMAGINE]      │ │  [IMMAGINE]      │
│                  │ │                  │ │                  │ │                  │
│  Epilazione      │ │  Trattamenti     │ │  Nail Center     │ │  Solarium        │
│  Laser           │ │  Corpo & T-Shape │ │                  │ │                  │
│                  │ │                  │ │                  │ │                  │
│  Risultati       │ │  Rimodella,      │ │  Manicure,       │ │  Abbronzatura    │
│  duraturi su     │ │  rassoda e       │ │  pedicure e      │ │  professionale   │
│  tutti i         │ │  leviga con      │ │  nail art con    │ │  con collagene   │
│  fototipi.       │ │  tecnologia      │ │  le ultime       │ │  solare.         │
│                  │ │  FDA-approved.   │ │  tendenze.       │ │                  │
│  [ Scopri ]      │ │  [ Scopri ]      │ │  [ Scopri ]      │ │  [ Scopri ]      │
│                  │ │                  │ │                  │ │                  │
└──────────────────┘ └──────────────────┘ └──────────────────┘ └──────────────────┘
```

**Card 1 — Epilazione Laser**
- **Titolo:** Epilazione Laser
- **Beneficio principale:** Risultati duraturi su tutti i fototipi, anche su pelle abbronzata.
- **Dettaglio:** Tecnologia EPILED 818 — laser a diodo di nuova generazione.
- **CTA:** `Scopri il trattamento →`

**Card 2 — Trattamenti Corpo & T-Shape**
- **Titolo:** Trattamenti Corpo & T-Shape
- **Beneficio principale:** Rimodella, rassoda e leviga con tecnologia FDA-approved.
- **Dettaglio:** 4 tecnologie in un unico dispositivo: radiofrequenza, laser, vacuum, mesoporesi.
- **CTA:** `Scopri il trattamento →`

**Card 3 — Nail Center**
- **Titolo:** Nail Center
- **Beneficio principale:** Manicure, pedicure e nail art con le ultime tendenze.
- **Dettaglio:** Un team di nail technician specializzate sempre aggiornate.
- **CTA:** `Scopri il trattamento →`

**Card 4 — Solarium**
- **Titolo:** Solarium
- **Beneficio principale:** Abbronzatura professionale con collagene solare.
- **Dettaglio:** Lettini alta e bassa pressione, docce solari, lampade viso.
- **CTA:** `Scopri il trattamento →`

**Link in fondo:** `Vedi tutti i servizi →` (link alla pagina Servizi o al menu)

**Componenti:**
- 4 card in griglia (desktop) / slider o stack (mobile)
- Ogni card: immagine, titolo H3, testo breve, CTA link

**Note UX:**
- Ordine delle card rispecchia le priorità del README (laser > corpo > nail > solarium)
- Le card devono essere cliccabili in toto (non solo la CTA)
- Su mobile: card in colonna singola o carosello swipeable

---

### SEZIONE 4 — PERCHÉ SCEGLIERCI

**Obiettivo:** Consolidare la fiducia e differenziare Love Sun dalla concorrenza.

**H2:** Perché scegliere Love Sun

```
┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│  🔬              │  │  🎓              │  │  💬              │
│  Tecnologie     │  │  Professioniste  │  │  Consulenza     │
│  Avanzate       │  │  Qualificate     │  │  Gratuita       │
│                 │  │                 │  │                 │
│  Utilizziamo    │  │  Il nostro team  │  │  Prima di ogni  │
│  macchinari     │  │  si aggiorna     │  │  percorso una   │
│  di ultima      │  │  continuamente   │  │  consulenza     │
│  generazione    │  │  sulle ultime    │  │  personalizzata │
│  certificati.   │  │  tecniche.       │  │  senza impegno. │
└─────────────────┘  └─────────────────┘  └─────────────────┘

┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│  📍              │  │  ⏰              │  │  🎁              │
│  Due Centri     │  │  Orari Flessibili│  │  Programma      │
│  in Lombardia   │  │                 │  │  Fedeltà        │
│                 │  │                 │  │                 │
│  Bregnano (CO)  │  │  Aperto fino    │  │  Ogni           │
│  e Carugate     │  │  alle 21:00.    │  │  trattamento    │
│  (MI), vicino   │  │  Domenica       │  │  ti avvicina    │
│  a te.          │  │  inclusa.       │  │  a un premio.   │
└─────────────────┘  └─────────────────┘  └─────────────────┘
```

**6 blocchi (griglia 3×2):**

1. **Tecnologie Avanzate** — Utilizziamo macchinari di ultima generazione certificati. EPILED 818 per l'epilazione laser, T-Shape 2 con certificazione FDA per i trattamenti corpo.
2. **Professioniste Qualificate** — Il nostro team si aggiorna continuamente sulle ultime tecniche e prodotti. Anni di esperienza al servizio della tua bellezza.
3. **Consulenza Gratuita** — Prima di iniziare qualsiasi percorso, ti offriamo una consulenza personalizzata senza impegno per trovare il trattamento più adatto a te.
4. **Due Centri in Lombardia** — Siamo presenti a Bregnano (Como) e Carugate (Milano). Sempre vicini a te.
5. **Orari Flessibili** — Aperti fino alle 21:00 dal lunedì al sabato e la domenica mattina. Perché la cura di te non deve aspettare.
6. **Programma Fedeltà** — Ogni trattamento conta. Con il programma fedeltà Love Sun accumuli punti e accedi a vantaggi esclusivi.

**Componenti:**
- Griglia 3×2 desktop / stack mobile
- Icona + titolo H3 + testo breve per ogni blocco
- Nessuna CTA in questa sezione (sezione informativa/trust)

---

### SEZIONE 5 — OFFERTE DEL MESE

**Obiettivo:** Massimizzare la conversione immediata sfruttando urgency e vantaggio economico.

**H2:** Offerte del Mese

**H3 (sottotitolo):** Approfitta dei nostri trattamenti in promozione. Disponibili fino ad esaurimento posti.

```
┌──────────────────────────────┐  ┌──────────────────────────────┐
│  🔥 OFFERTA DEL MESE         │  │  🔥 OFFERTA DEL MESE         │
│                              │  │                              │
│  Epilazione Laser            │  │  T-Shape Corpo               │
│  Gambe Complete              │  │  Pacchetto 5 sedute          │
│                              │  │                              │
│  ~~€ 180~~  → € 129          │  │  ~~€ 350~~  → € 269          │
│                              │  │                              │
│  Scade il 30 giugno          │  │  Scade il 30 giugno          │
│                              │  │                              │
│  [ Prenota Ora ]             │  │  [ Prenota Ora ]             │
└──────────────────────────────┘  └──────────────────────────────┘
```

**Struttura di ogni card offerta:**
- Label badge "Offerta del Mese" (o "Promozione" / "Esclusiva Web")
- Titolo del trattamento
- Prezzo barrato → Prezzo scontato
- Data di scadenza
- CTA: `Prenota Ora`

**Nota:** I prezzi reali andranno inseriti dal cliente. Le card sono strutture dinamiche aggiornabili mensilmente.

**Link in fondo:** `Vedi tutte le offerte →` (link a pagina Offerte del Mese)

**Componenti:**
- 2 card offerta affiancate (desktop) / stack (mobile)
- Badge colorato per la promozione
- Prezzo con strike-through sul vecchio prezzo
- Countdown opzionale se si vuole aumentare urgency
- CTA diretta per ogni offerta

**Note UX:**
- Questa sezione deve avere un visual distintivo (sfondo leggermente diverso) per separare dal resto
- Il contrasto tra prezzo vecchio e nuovo deve essere netto e leggibile
- Non usare claim aggressivi (es. "SOLO PER OGGI!!!") — mantenere tono professionale

---

### SEZIONE 6 — RECENSIONI

**Obiettivo:** Consolidare la fiducia attraverso la voce delle clienti reali.

**H2:** Cosa dicono le nostre clienti

**H3 (sottotitolo):** 4,9 su 5 su Treatwell · Oltre 419 recensioni verificate

```
┌────────────────────────────────────────────────────────────────────┐
│                                                                    │
│   ⭐⭐⭐⭐⭐        ⭐⭐⭐⭐⭐        ⭐⭐⭐⭐⭐                         │
│                                                                    │
│  "È la prima volta    "Un'accoglienza     "Staff gentilissimo,    │
│  che vengo da         pazzesca e          si lavora con           │
│  Lovesun ma penso     davvero una         entusiasmo."            │
│  di aver trovato      grande gentilezza                           │
│  il mio centro        e professionalità." — Cliente verificata    │
│  estetico per                             Treatwell               │
│  sempre!"             — Cliente verificata                        │
│                       Treatwell                                   │
│  — Cliente verificata                                             │
│    Treatwell                                                       │
│                                                                    │
│              [ ← ]  ●  ●  ●  ●  ●  [ → ]                        │
│                                                                    │
│          [ Leggi tutte le recensioni su Treatwell ]               │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

**Elementi:**
- Rating aggregato visibile: ⭐ 4,9/5 · 419 recensioni
- Slider di 5–6 recensioni (testo + stelle + fonte "Cliente verificata su Treatwell")
- Indicatori di navigazione (dots)
- Link esterno: "Leggi tutte le recensioni su Treatwell"

**Testimonianze da usare:**

> *"È la prima volta che vengo da Lovesun Solarium, ma penso di aver trovato il mio centro estetico per sempre! Grazie Michelle, le tue mani delicate mi hanno conquistata!"*

> *"Un'accoglienza pazzesca e davvero una grande gentilezza e professionalità, le persone sono socievoli e le ragazze simpaticissime."*

> *"Staff gentilissimo, si lavora con entusiasmo."*

> *"Accoglienza ottima, con grande gentilezza e professionalità."*

> *"Alessandro è molto gentile e disponibile."*

> *"Le ragazze sono molto cortesi e disponibili."*

**Componenti:**
- Carosello recensioni con autoplay lento (5s) e controllo manuale
- Stelle visibili per ogni recensione
- Logo/badge Treatwell come fonte di credibilità
- Su mobile: una recensione per volta, swipe

**Note UX:**
- Le recensioni che citano nomi dello staff sono le più credibili — metterle in evidenza
- Non modificare il testo delle recensioni — autenticità è fondamentale
- Il link a Treatwell apre in nuova scheda

---

### SEZIONE 7 — SEDI

**Obiettivo:** Aiutare l'utente a identificare la sede più vicina e portarlo alla prenotazione specifica.

**H2:** Dove siamo

```
┌──────────────────────────────────┐  ┌──────────────────────────────────┐
│                                  │  │                                  │
│  📍 Love Sun Bregnano            │  │  📍 Love Sun Carugate            │
│                                  │  │                                  │
│  Via per Lazzate 7               │  │  Via del Ginestrino 16           │
│  22070 Bregnano (CO)             │  │  20061 Carugate (MI)             │
│                                  │  │                                  │
│  ☎ 031-4682567                   │  │  ☎ 02-7709-5069                  │
│  📱 +39 347 398 3337             │  │  💬 WhatsApp 331-1093564         │
│                                  │  │                                  │
│  Lun–Sab: 08:30–21:00            │  │  Mar–Mer: 09:00–20:00            │
│  Dom: 09:00–15:00                │  │  Gio: 09:00–21:00                │
│                                  │  │  Ven–Sab: 09:00–19:00           │
│                                  │  │  Lun–Dom: Chiuso                 │
│                                  │  │                                  │
│  [ Prenota a Bregnano ]          │  │  [ Prenota a Carugate ]          │
│  [ Come raggiungerci ]           │  │  [ Come raggiungerci ]           │
│                                  │  │                                  │
│  [MAPPA EMBED]                   │  │  [MAPPA EMBED]                   │
│                                  │  │                                  │
└──────────────────────────────────┘  └──────────────────────────────────┘
```

**Card Bregnano:**
- Indirizzo: Via per Lazzate 7, 22070 Bregnano (CO)
- Tel: 031-4682567 / +39 347 398 3337
- Orari: Lun–Sab 08:30–21:00 | Dom 09:00–15:00
- CTA 1: `Prenota a Bregnano` → Treatwell Bregnano
- CTA 2: `Come raggiungerci` → Google Maps
- Mappa embed Google Maps

**Card Carugate:**
- Indirizzo: Via del Ginestrino 16, 20061 Carugate (MI)
- Tel: 02-7709-5069
- WhatsApp: 331-1093564
- Orari: Mar–Gio 09:00–20:00 (Gio fino 21) | Ven–Sab 09:00–19:00 | Lun e Dom chiuso
- CTA 1: `Prenota a Carugate` → Treatwell Carugate
- CTA 2: `Scrivici su WhatsApp` → wa.me
- Mappa embed Google Maps

**Componenti:**
- 2 card affiancate (desktop) / stack (mobile)
- Ogni card: nome sede, indirizzo, orari, telefono/WhatsApp, mappa embed, 2 CTA
- Icone per telefono / WhatsApp / orari

**Note UX:**
- Carugate è la sede prioritaria (da README) — valutare se posizionarla a sinistra o darle un visual badge "Sede Milano"
- WhatsApp di Carugate deve essere CTA cliccabile diretta
- Mappe embed aumentano il tempo sulla pagina e riducono la necessità di uscire per trovare le indicazioni
- Su mobile: card in colonna, mappa collassata con "Mostra mappa"

---

### SEZIONE 8 — CTA FINALE

**Obiettivo:** Ultima opportunità di conversione prima del footer. Catturare chi ha letto ma non ha ancora agito.

**H2:** Pronta a prenderti cura di te?

**Body:** Prenota il trattamento più adatto a te o contattaci per una consulenza gratuita e personalizzata. Il nostro team è a tua disposizione.

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│         Pronta a prenderti cura di te?                         │
│                                                                 │
│  Prenota il trattamento più adatto o richiedi una consulenza    │
│  gratuita. Il nostro team è a tua disposizione.                 │
│                                                                 │
│   [ 📅 Prenota Online ]  [ 💬 WhatsApp ]  [ 📞 Chiama Ora ]    │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

**3 CTA affiancate:**

1. `📅 Prenota Online` → Treatwell (CTA primaria, visivamente dominante)
2. `💬 Scrivici su WhatsApp` → wa.me/3311093564
3. `📞 Chiama Ora` → tel:0314682567

**Note UX:**
- Sfondo differenziato per far risaltare la sezione
- Le 3 CTA devono avere gerarchia visiva chiara: Prenota > WhatsApp > Telefono
- Su mobile: CTA in colonna, tutta l'area toccabile
- Questa sezione è l'ancora per la CTA secondaria dell'hero ("Consulenza Gratuita")

---

### FOOTER

**Struttura a 4 colonne (desktop) / accordion (mobile):**

**Colonna 1 — Brand**
- Logo Love Sun
- Tagline breve: "Beauty Center. Bellezza e benessere in Lombardia."
- Social: Facebook | Instagram | TikTok

**Colonna 2 — Servizi**
- Epilazione Laser
- Trattamenti Corpo & T-Shape
- Solarium
- Nail Center
- Cerette
- Pedicure
- Pulizia Viso
- Massaggi

**Colonna 3 — Love Sun Bregnano**
- Via per Lazzate 7, 22070 Bregnano (CO)
- Tel: 031-4682567
- +39 347 398 3337
- Lun–Sab 08:30–21:00 | Dom 09:00–15:00

**Colonna 4 — Love Sun Carugate**
- Via del Ginestrino 16, 20061 Carugate (MI)
- Tel: 02-7709-5069
- WhatsApp: 331-1093564
- Mar–Ven 09:00–20:00 (Gio 21) | Sab 09:00–19:00

**Bottom bar:**
- © 2026 Love Sun · Privacy Policy · Cookie Policy · P.IVA [da inserire]

**Componenti:**
- Griglia 4 colonne desktop
- Accordion collassabile mobile
- Icone social cliccabili
- Tutti i numeri cliccabili (tel: link)

---

## Elementi Persistenti — Mobile

**WhatsApp Button Flottante:**
- Icona WhatsApp fissa in basso a destra
- Sempre visibile durante lo scroll
- Link diretto: wa.me/3311093564

**Motivazione:** Su mobile il canale WhatsApp è il più immediato. Un bottone flottante riduce il friction a zero.

---

## Note UX Generali — Home Page

| Elemento | Nota |
|----------|------|
| Velocità | Hero statico (no slider), immagini ottimizzate — priorità performance |
| Mobile first | Il 70%+ del traffico arriverà da mobile — progettare prima per smartphone |
| Gerarchia CTA | Una sola CTA primaria per schermata, le secondarie non devono competere |
| Scroll depth | Le sezioni più importanti (Trust Bar, Servizi, Offerte) devono stare nella prima schermata mobile |
| SEO | H1 unico, H2 per ogni sezione, alt text su tutte le immagini |
| Accessibilità | Contrasto testo/sfondo WCAG AA minimo, testo alternativo per ogni immagine |
| Trust | Non modificare mai il testo delle recensioni reali |
| Tono | Professionale, accogliente — nessuna pressione commerciale aggressiva |

---

## Obiettivi di Conversione — Metriche di Riferimento

| Conversione | Posizione nel layout | Frequenza |
|-------------|---------------------|-----------|
| Prenotazione Treatwell | Header + Hero + Sedi + CTA Finale | 4 punti |
| WhatsApp | Header + Sedi (Carugate) + CTA Finale + Flottante mobile | 4+ punti |
| Telefono | Header + Sedi + CTA Finale | 3 punti |
| Consulenza Gratuita | Hero (CTA secondaria) + Sezione Perché Sceglierci | 2 punti |
| Offerte | Sezione dedicata | 1 punto |

---

## Checklist Componenti Necessari

- [ ] Immagine hero (donna trattamento, professionale ed emozionale)
- [ ] Immagini per ogni card servizio (4 immagini)
- [ ] Icone per trust bar (4)
- [ ] Icone per "Perché sceglierci" (6)
- [ ] Carosello recensioni (componente JS)
- [ ] Badge Treatwell
- [ ] Google Maps embed (2 mappe)
- [ ] Logo Love Sun (versione chiara e scura)
- [ ] Icone social (Facebook, Instagram, TikTok)
- [ ] WhatsApp button flottante (mobile)
- [ ] Sticky header con CTA

---

*Fine wireframe Home Page*
*Prossimo step: Wireframe — Epilazione Laser*
