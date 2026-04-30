# DOOM/SCROLL — Backlog
*Documento di lavoro. Cancelliamo le voci man mano che vengono implementate con successo.*

---

## STATO ATTUALE

**Ultima sessione:** maxi review pre-lancio + C1 + C2 + C3 rimosso + B3 Giulia/Elisa + immagini
**Versione corrente:** 3.3.0 — pronto per lancio pubblico

---

## SEZIONE A — FUTURE FEATURE (post-lancio)

### A. Easter egg rotellina veloce
Quando l'utente scrolla troppo veloce con la rotellina, triggera qualcosa. Da definire cosa.

### B. Chat Giulia — eventuali fix narrativi post-feedback
Dopo il lancio, raccogliere feedback sulla conversazione e affinare se necessario.

### C. A7 header redesign completo
Il degrado col QI è implementato, ma il redesign visivo vero e proprio (A7) è rimandato a post-lancio. Da fare come sessione dedicata.

---

## PROMEMORIA / NON-CODE

- **Immagine 11 (lobotomia social)** — riservata per campagne sponsorizzazione/marketing. Non usare nel gioco.
- **Immagine 2 (anatomica verticale)** — sfondo feed QI < 5 ✅ implementata.

---

## SEZIONE D — GIÀ FATTE

**Core originale**
- ~~Splash screen iniziale~~ ✅
- ~~Pressione crescente nel loop~~ ✅
- ~~Riga pre-finale~~ ✅
- ~~Sesto finale segreto "santo"~~ ✅ testato online
- ~~Notifica diegetica + conversazione Giulia~~ ✅
- ~~Audio ambient con AudioContext~~ ✅

**v3.0.1**
- ~~A1: Quit definitivo riprogettato~~ ✅
- ~~Bugfix modali + restart + animazione pre-finale~~ ✅

**v3.1.0**
- ~~Trigger quit: opzione D (everIgnored || adClicks >= 1)~~ ✅
- ~~Toast: max 2, 3.5s, pulizia al finale, bottom fisso~~ ✅
- ~~Bugfix quit overlay (position:relative rimosso)~~ ✅

**v3.2.0**
- ~~A2: Feeling avvicinamento finali~~ ✅ — nirvana 4 soglie QI, brainrot hint bottone, quit whisper
- ~~A4: Espansione card notizie con toast pool~~ ✅
- ~~A5: Commenti strutturati (57 commenti, autore + reazioni)~~ ✅
- ~~A6: Filone antifascismo (34 titoli, 6 angolazioni)~~ ✅
- ~~A6: Sources rielaborate (27 giochi di parole)~~ ✅
- ~~A7: Header degrada col QI (4 soglie)~~ ✅
- ~~A8: Screenshot finale → PNG Canvas API~~ ✅
- ~~A9: Timestamp che ti tradisce (salta dopo 5 min)~~ ✅
- ~~A10: Nirvana che non finisce (zombie cards + countdown restart)~~ ✅
- ~~A11: Continuità tra partite (sessione N, statistiche cumulative)~~ ✅
- ~~B1: La X che non è un'opzione~~ ✅
- ~~B2: Commentary mode (7 click red dot)~~ ✅
- ~~Flush command (digita "flush")~~ ✅
- ~~Lobotomy command (digita "lobotomy" → -50 QI)~~ ✅
- ~~JSON consolidato (content.json con tutte le nuove chiavi)~~ ✅

**v3.3.0**
- ~~B3: Chat Giulia — riscritta con albero a 3 livelli~~ ✅
- ~~Elisa: notifica arrabbiata con delay 5-10s, 3 livelli di rabbia~~ ✅
- ~~convInProgress — silenzio toast/cervello durante conversazione~~ ✅
- ~~Bug notifica QI<55 non scattava (fix timer tick)~~ ✅
- ~~Santo ending — testo riscritto (genuino + ambiguo)~~ ✅
- ~~Lercio: badge SATIRA rimosso, bordo 2px neutro~~ ✅
- ~~C1: metaAware — dopo card meta, frequenza Lercio raddoppia per 2 load~~ ✅
- ~~C2: anti-bot overlay + debug mode (fonti e tag in modalità raw)~~ ✅
- ~~C3: SISTEMA rimosso completamente~~ ✅
- ~~Sfondo lobotomia — immagine anatomica fixed a QI < 5~~ ✅
- ~~Brainrot post card (average brainrot user experience)~~ ✅
- ~~Easter egg lobotomy card nel feed (load 8-12)~~ ✅
- ~~Maxi review pre-lancio (localStorage protetti, toast cap fix, variabili morte)~~ ✅
