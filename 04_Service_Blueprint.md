# Service Blueprint: "Lokalhjerte"
## Digital Plattform for Mikro-Frivillighet i Bydel Østensjø

---

# TJENESTENAVNET: **LOKALHJERTE**

**Tagline:** "Gi 2 timer. Få mening tilbake."

**Konsept:**
En digital plattform som matcher voksne 50-65 år med korte, meningsfulle frivilligoppgaver i sitt nærområde - basert på deres kompetanse, interesser og tilgjengelige tid.

**Kjerneprinsipp:**
Frivillighet skal være like enkelt som å bestille kinobilletter. Klar oppgave. Velg tid. Gjennomfør. Få takk. Gjenta.

---

# SERVICE BLUEPRINT: BRUKERREISE "FØRSTE OPPDRAG"

## Horisontale Lag (Front-stage til Back-stage)

```
═══════════════════════════════════════════════════════════════════════
                         PHYSICAL EVIDENCE
═══════════════════════════════════════════════════════════════════════
                         CUSTOMER ACTIONS
───────────────────────────────────────────────────────────────────────
LINE OF INTERACTION
───────────────────────────────────────────────────────────────────────
                         FRONTSTAGE ACTIONS (Synlig for bruker)
───────────────────────────────────────────────────────────────────────
LINE OF VISIBILITY
───────────────────────────────────────────────────────────────────────
                         BACKSTAGE ACTIONS (Usynlig for bruker)
───────────────────────────────────────────────────────────────────────
LINE OF INTERNAL INTERACTION
───────────────────────────────────────────────────────────────────────
                         SUPPORT PROCESSES
═══════════════════════════════════════════════════════════════════════
```

---

## FASE 1: ONBOARDING (Bli Med)

### PHYSICAL EVIDENCE
- Facebook-innlegg / Instagram-annonse
- Lokalhjerte.no landingsside
- Mobilapp (iOS/Android)
- QR-kode på plakater (bibliotek, Cafe X)

### CUSTOMER ACTIONS
1. Ser Facebook-innlegg: "Test: Hva slags frivillig er du?"
2. Klikker lenke → ankommer Lokalhjerte.no
3. Tar 2-minutters quiz:
   - Alder, yrkesstatus, bosted
   - Kompetanse (velg 3): Pedagogikk, IT, Praktisk, Kreativ, Sosialt, etc.
   - Tilgjengelig tid: 1-3t/mnd, 4-8t/mnd, 8+t/mnd
   - Preferanser: Innendørs/utendørs, Alene/gruppe, Fast/fleksibelt
4. Oppretter profil (Facebook-login eller e-post)
5. Får øyeblikkelig forslag: "3 oppdrag matcher deg!"

### FRONTSTAGE ACTIONS (Synlig)
- Velkomstmelding: "Hei [Navn]! La oss finne det perfekte oppdraget for deg."
- Quiz-interface (enkel, visuell, mobil-vennlig)
- Matching-resultater vises umiddelbart
- E-post: "Velkommen til Lokalhjerte! Dine matches:"

### BACKSTAGE ACTIONS (Usynlig)
- CRM registrerer ny bruker
- Matching-algoritme kjører:
  - Kompetanse → Oppgave-tags
  - Tid → Oppgave-lengde
  - Bosted → Lokasjon
- Segmenterer bruker (Persona: Marit, Per, Kari, Lise)
- Trigger velkomst-workflow

### SUPPORT PROCESSES
- Database: Brukerprofi ler, Oppgaver, Matching-regler
- Algoritme: Collaborative filtering + rule-based matching
- E-post-system: Automatisk velkomst + match-notifikasjon
- Analytics: Spor conversion rate (quiz → profil)

**💡 KRITISK SUKSESSFAKTOR:**
Quiz må ta <2 min. Over 2 min = 50% drop-off.

---

## FASE 2: FØRSTE OPPDRAG (Prøv)

### PHYSICAL EVIDENCE
- Push-notifikasjon på mobil
- E-post med oppgavedetaljer
- Kalenderinvitasjon (.ics fil)
- SMS-påminnelse

### CUSTOMER ACTIONS
1. Ser notifikasjon: "Nytt oppdrag matcher deg: IT-hjelp til eldre (2t)"
2. Klikker → leser oppgavebeskrivelse:
   - **Hva:** Hjelp 5 eldre med Vipps/BankID (1-til-1 veiledning)
   - **Hvor:** Oppsal frivillighetssentral (kart embedded)
   - **Når:** Velg dato: Lør 11.nov, Lør 18.nov, Søn 19.nov (alle kl 10-12)
   - **Kontakt:** Kaja Hansen (bilde + mobil)
3. Velger "Lørdag 18. november 10-12"
4. Klikker "Meld meg på"
5. Får bekreftelse: "Du er påmeldt! Vi gleder oss 😊"

### FRONTSTAGE ACTIONS (Synlig)
- Oppgavekort vises i app/web:
  - Tittel, beskrivelse, ikon, varighet
  - Tydelig "Hva du skal gjøre" (bulletpoints)
  - "Hva du får" (opplæring, kaffe, sertifikat)
  - Antall plasser (f.eks. "3 av 5 ledige")
- Interaktiv kalendervelger
- Bekreftelsesside med:
  - Oppsummering
  - "Legg til i kalenderen" (Google/Outlook)
  - Kontaktinfo til Kaja
- SMS: "Hei [Navn]! Bekreftet: IT-hjelp 18.nov 10-12. Kaja kontakter deg i morgen."

### BACKSTAGE ACTIONS (Usynlig)
- System registrerer påmelding
- Oppdaterer oppgave-kapasitet (5 → 4 ledige plasser)
- Trigger bekreftelse-workflow:
  - E-post til bruker
  - SMS til bruker
  - Notifikasjon til Kaja (koordinator): "Per Hansen (62) meldt på IT-hjelp 18.nov"
- Legger til event i brukerens Lokalhjerte-kalender
- Setter reminder (7 dager før, 1 dag før)

### SUPPORT PROCESSES
- Påmeldingssystem: Real-time kapasitetshåndtering
- CRM: Logger brukeraktivitet
- SMS-gateway: Automatisk bekreftelse
- Koordinator-dashboard: Kaja får oversikt over påmeldte (navn, alder, kompetanse, kontaktinfo)

**💡 KRITISK SUKSESSFAKTOR:**
Umiddelbar bekreftelse (< 10 sekunder). Forsinket bekreftelse = usikkerhet = drop-off.

---

## FASE 3: PRE-OPPDRAG (Forberedelse)

### PHYSICAL EVIDENCE
- E-post fra Kaja (personlig)
- SMS-påminnelse (automatisk)
- Oppgaveguide (PDF nedlastbar i app)

### CUSTOMER ACTIONS
1. Dag 1: Mottar e-post fra Kaja:
   - "Hei Per! Så fint at du blir med. Her er hva vi skal gjøre..."
   - Vedlegg: "Guide: Vanlige Vipps-spørsmål"
2. Dag 6: Mottar påminnelse-SMS:
   - "Husk: I morgen kl 10 IT-hjelp. Parkering: Bak biblioteket (gratis). Kaja møter deg ved inngangen."
3. Leser guiden, føler seg forberedt

### FRONTSTAGE ACTIONS (Synlig)
- Personlig e-post fra Kaja (ikke templat-følelse)
- SMS med praktisk info (parkering, hvor møte)
- Nedlastbar guide i app (kan lese offline)

### BACKSTAGE ACTIONS (Usynlig)
- CRM sender reminder til Kaja: "Husk å kontakte Per innen 3 dager før oppdraget"
- Kaja skriver personlig e-post (bruk av mal, men tilpasser)
- System sender automatisk SMS 24t før (fra templat)
- Analytics: Spor "no-show rate" (hvis høy, juster reminder-timing)

### SUPPORT PROCESSES
- E-post-system: Template-bibliotek for koordinatorer
- SMS-scheduler: Automatisk 24t-reminder
- Ressursbibliotek: Guider, FAQ, videoer for ulike oppgaver
- Koordinator-CRM: Påminnelser om oppfølging

**💡 KRITISK SUKSESSFAKTOR:**
Personlig touch fra koordinator = 90% oppmøte. Bare automatisk SMS = 60% oppmøte.

---

## FASE 4: OPPGAVE-GJENNOMFØRING (Opplev)

### PHYSICAL EVIDENCE
- Oppsal frivillighetssen tral (fysisk lokasjon)
- Skilt: "Lokalhjerte IT-hjelp i dag kl 10-12"
- Navneskilt for frivillige
- Kaffekopp med Lokalhjerte-logo
- Arbeidsområde med PC-er, stikk, wifi

### CUSTOMER ACTIONS
1. Ankommer kl 09:55
2. Møtes av Kaja ved inngangen
3. Får kort introduksjon (5 min):
   - "Dette er opplegget..."
   - "Her er de 5 deltakerne (navn, alder, hva de trenger hjelp til)"
   - "Jeg er her hele tiden hvis du lurer på noe"
4. Jobber 1-til-1 med eldre deltakere (2 timer)
5. Kaffepause (15 min) - småprater med andre frivillige
6. Avslutter, får takk fra deltakerne
7. Får takk fra Kaja + "Håper du vil være med igjen!"

### FRONTSTAGE ACTIONS (Synlig)
- **Kaja (Koordinator):**
  - Varm velkomst ved døren
  - Introduksjon til opplegget
  - Presenterer Per for deltakerne
  - Sirkulerer, tilbyr støtte
  - Kaffepause-fasilitator (sørger for at folk prater)
  - Avslutter med takk + inviterer til neste
- **Fysisk miljø:**
  - Ryddig, lyst lokale
  - Navneskilt, kaffe, mat
  - Lokalhjerte-materiell (gir identitet)

### BACKSTAGE ACTIONS (Usynlig)
- Kaja har forberedt:
  - Deltakerliste (navn, aldri, hva de trenger hjelp til)
  - PC-er/nettbrett klare
  - Kaffe/kaker bestilt
  - Sjekkliste for introduksjon
- Under oppdraget:
  - Kaja observerer (er Per komfortabel? Trenger han hjelp?)
  - Logger eventuelle problemer (for forbedring)
- Etter oppdraget:
  - Kaja logger oppmøte i CRM (Per dukket opp ✅)
  - Noterer observasjoner ("Per var utmerket, passet perfekt!")

### SUPPORT PROCESSES
- Koordinator-trening: "Hvordan lede et Lokalhjerte-oppdrag"
- Oppgavemaler: Sjekklister for ulike oppgavetyper
- Ressurser: PC-er, wifi, materiell
- Partnere: Oppsal frivillighetssentral (lokale), Cafe X (kaffe)

**💡 KRITISK SUKSESSFAKTOR:**
Koordinators evne til å skape trygg, varm atmosfære = #1 faktor for at Per kommer igjen.

---

## FASE 5: UMIDDELBAR OPPFØLGING (Takk)

### PHYSICAL EVIDENCE
- SMS (samme dag)
- E-post med bilder (neste dag)
- Impact-rapport (PDF)

### CUSTOMER ACTIONS
1. Kl 15:00 (samme dag): Mottar SMS:
   - "Tusen takk Per! 5 eldre mestrer nå Vipps og BankID takket være deg. Du reddet Solveig fra svindel-SMS i dag! 🎉"
2. Dag 2: Mottar e-post med:
   - Bilde fra oppdraget (anonymt, eller med samtykke)
   - Sitater fra deltakere: "Per var så tålmodig!" - Solveig, 76 år
   - Impact: "5 personer, 10 timer opplæring, 100% mestret Vipps"
3. Leser, føler stolthet
4. Deler på Facebook: "Hadde en flott dag som frivillig IT-mentor! 💚"

### FRONTSTAGE ACTIONS (Synlig)
- SMS: Personlig, spesifikk (nevner Solveig + svindel-SMS)
- E-post: Visuell, engasjerende (bilder + sitater)
- Sosiale medier: Enkel delingsknapp i e-post ("Del din Lokalhjerte-opplevelse")

### BACKSTAGE ACTIONS (Usynlig)
- Kaja logger i CRM: "Oppdraget vellykket"
- System trigger "Takk-workflow":
  - SMS genereres automatisk (template, men Kaja kan redigere for å personalisere)
  - E-post sendes neste dag (Kaja laster opp bilde, legger til sitater)
- Analytics: Spor "deling på sosiale medier" (hvis Per deler → track)
- CRM oppdaterer Pers profil: "Kompetanse: IT-mentor ✅, Erfaring: 1 oppdrag, Feedback: Positiv"

### SUPPORT PROCESSES
- SMS-system: Automatisk trigger post-oppgave
- E-post-system: Template for impact-rapport
- Fotoarkiv: Lagrer bilder (GDPR-compliant, samtykke)
- Analytics: Måler "share rate" + "repeat rate"

**💡 KRITISK SUKSESSFAKTOR:**
Umiddelbar anerkjennelse (samme dag) øker "intent to return" med 70%.

---

## FASE 6: RE-ENGAGEMENT (Kom Tilbake)

### PHYSICAL EVIDENCE
- Push-notifikasjon (app)
- E-post med ny invitasjon
- In-app "Dine foreslåtte oppdrag"

### CUSTOMER ACTIONS
1. 2 uker etter første oppdrag: Mottar e-post:
   - "Hei Per! Vi trenger deg igjen 😊 Nytt IT-kurs: Digital Sikkerhet (6 fredager)"
2. Klikker, leser beskrivelse:
   - **Hva:** Hololde kurs for eldre om phishing, passord, svindel (du designer kurset!)
   - **Når:** 6 fredager i januar-februar (kl 16-18)
   - **Autonomi:** Du får full frihet til å lage opplegg
3. Tenker "Dette er perfekt! Jeg får lage noe selv!"
4. Melder seg på
5. **Blir langsiktig frivillig**

### FRONTSTAGE ACTIONS (Synlig)
- Personlig e-post: "Vi trenger deg igjen" (ikke generisk)
- Oppgave tilpasset hans kompetanse + tidligere erfaring
- Fremhever autonomi ("du designer kurset")
- Kaja ringer (ikke bare e-post): "Hei Per, jeg tenkte på deg til dette..."

### BACKSTAGE ACTIONS (Usynlig)
- CRM analyserer Pers profil:
  - Kompetanse: IT
  - Preferanse: Pedagogisk (observert i første oppgave)
  - Tilgjengelig tid: Kvelder
  - Matching-score: IT-kurs = 95% match
- System foreslår oppgave til Kaja: "Per er perfekt for IT-kurs"
- Kaja godkjenner, sender personlig invitasjon (e-post + oppfølging på telefon)

### SUPPORT PROCESSES
- Matching-algoritme: Lærer fra hver interaksjon (Per likte autonomi → prioriter prosjektbaserte oppgaver)
- CRM-workflow: Auto-foreslår re-engagement etter 2 uker
- Koordinator-dashboard: "Foreslåtte matches" (Kaja godkjenner)
- Analytics: Spor "repeat rate" (% som tar 2. oppgave)

**💡 KRITISK SUKSESSFAKTOR:**
Personlig oppfølging (e-post + telefon) fra Kaja = 80% accept rate. Bare e-post = 40%.

---

---

# KOMPLETT SERVICE ECOSYSTEM

## BRUKERSEGMENTER

### Primærbrukere (Frivillige 50-65)
- **Marit** (Sandwichgenerasjonen): Mikro-oppdrag
- **Per** (Pre-pensjonist): Prosjektbasert
- **Kari** (Aktiv pensjonist): Fast ukentlig
- **Lise** (Nølende): Lav-terskel

### Sekundærbrukere
- **Mottakere** (Eldre, ensomme): Får tjenester
- **Koordinator** (Kaja): Administrerer
- **Admin** (Bydel Østensjø): Måler impact

## TOUCHPOINTS

### Digitale
1. **Lokalhjerte.no** (Web)
2. **Lokalhjerte App** (iOS/Android)
3. **Facebook** (Gruppe + Annonser)
4. **Instagram** (Stories + Innlegg)
5. **E-post**
6. **SMS**
7. **Push-notifikasjoner**

### Fysiske
1. **Oppsal frivillighetssentral** (Lokale)
2. **Cafe X** (Sosiale treff)
3. **Deichman Oppsal bibliotek** (Samlokalisering)
4. **Plakater** (QR-koder)
5. **Frivillig-frokoster** (Månedlige events)

### Menneskelige
1. **Kaja (Koordinator)** - Personlig kontakt
2. **Ambassadører** (Erfarne frivillige)
3. **Venner** (Peer-to-peer rekruttering)

## BACKEND-SYSTEMER

### Teknologi
1. **CRM-system** (Bruker database)
   - Profiler (kompetanse, preferanser, historikk)
   - Segmentering (Persona-mapping)
   - Kommunikasjonshistorikk

2. **Matching-algoritme**
   - Kompetanse-matching
   - Tidsbasert matching
   - Collaborative filtering ("Personer som deg likte også...")

3. **Oppgavebibliotek**
   - Standardiserte oppgavemaler
   - Tags (kompetanse, varighet, format)
   - Kapasitetshåndtering (ledige plasser)

4. **Kommunikasjonsplattform**
   - E-post-automatisering (workflows)
   - SMS-gateway
   - Push-notifikasjoner

5. **Koordinator-dashboard**
   - Oversikt over påmeldte
   - Foreslåtte matches
   - Ressursbibliotek (guider, sjekklister)
   - Reporting (KPI-er)

6. **Analytics & Reporting**
   - Conversion funnels (quiz → profil → første oppgave → repeat)
   - Retention metrics
   - Impact-måling (timer, personer hjulpet)

### Organisasjon
1. **Kaja (Frivilligkoordinator)** - 50% stilling
   - Rekruttering (seed initial users)
   - Oppgavedesign (lage nye oppdrag)
   - Fasilitering (lede oppdrag)
   - Oppfølging (personlig kontakt)

2. **Digital Utvikler** - Konsulent (initial build)
   - App/web-utvikling
   - Matching-algoritme
   - Integrasjoner (Facebook, Google Calendar)

3. **Ambassador-team** - 5-10 erfarne frivillige
   - Peer-to-peer rekruttering
   - Onboarding-buddies
   - Feedback-loop til Kaja

4. **Bydel Østensjø Admin**
   - Budsjett og ressurser
   - Partnerskap (bibliotek, Cafe X)
   - KPI-rapportering

### Partnere
1. **Oppsal frivillighetssentral** (Lokale)
2. **Deichman Oppsal bibliotek** (Samlokalisering, deltakere)
3. **Cafe X** (Sosiale events, catering)
4. **Lokale bedrifter** (Corporate volunteering, sponsing)
5. **Pensjonistforeninger** (Rekruttering)
6. **NAV** (Henvisning av arbeidsledige)

---

# KEY PERFORMANCE INDICATORS (KPI)

## Rekruttering
- **Nye brukere/mnd:** 50 (mål år 1)
- **Conversion rate (quiz → profil):** >70%
- **Conversion rate (profil → første oppgave):** >50%
- **Peer-to-peer rekruttering:** 30% kommer via venn

## Engagement
- **Repeat rate (tar 2. oppgave):** >60%
- **Retention (aktiv etter 6 mnd):** >40%
- **Gjennomsnittlig oppdrag/bruker/år:** 6-8

## Impact
- **Timer frivillig arbeid/mnd:** 300 (mål år 1)
- **Personer hjulpet/mnd:** 100
- **NPS (Net Promoter Score):** >50

## Operasjonell effektivitet
- **Koordinator-tid per oppgave:** <2 timer (ned fra 5)
- **Automatiseringsgrad:** 70% av kommunikasjon
- **No-show rate:** <10%

---

# RISIKO & MITIGERING

| Risiko | Sannsynlighet | Konsekvens | Mitigering |
|--------|---------------|------------|------------|
| Lav initial påmelding | Middels | Høy | Seed med 50 brukere via direkte invitasjon (Kaja rekrutterer personlig) |
| Høy drop-off før første oppgave | Middels | Høy | Personlig oppfølging fra Kaja + lav-terskel oppdrag |
| Dårlig opplevelse første gang | Lav | Kritisk | Koordinator-trening + standardiserte onboarding-protokoller |
| Teknisk plattform for kompleks | Middels | Middels | Start med MVP (web-only, manuell matching) → iterer |
| Koordinator overbelastet | Høy | Middels | Automatiser kommunikasjon + tren ambassadører til å hjelpe |
| GDPR-brudd (data) | Lav | Kritisk | Juridisk gjennomgang + samtykke-flow + dataminimering |

---

# IMPLEMENTERINGSPLAN

## FASE 1: MVP (Måned 1-3)
**Mål:** Test konsept med 50 brukere, 5 oppgavetyper

**Leveranser:**
- Enkel landingsside (Lokalhjerte.no)
- Påmeldingsskjema (quiz)
- Manuell matching (Kaja matcher)
- E-post + SMS-templates
- 5 pilotoppdrag

**Team:**
- Kaja (koordinator) - full tid
- Web-utvikler (konsulent) - 40 timer
- Designer - 20 timer

**Budsjett:** 150.000 NOK

**Suksesskriterier:**
- 50 brukere påmeldt
- 30 gjennomførte oppdrag
- 60% repeat rate

---

## FASE 2: Skalering (Måned 4-9)
**Mål:** Voks til 200 brukere, 20 oppgavetyper, lansere app

**Leveranser:**
- Mobilapp (iOS/Android)
- Automatisk matching-algoritme
- CRM-integrasjon
- Ambassador-program (tren 10 ambassadører)
- Månedlige Frivillig-frokoster

**Team:**
- Kaja (koordinator) - full tid
- App-utvikler - 120 timer
- Marketing-konsulent - 40 timer

**Budsjett:** 400.000 NOK

**Suksesskriterier:**
- 200 aktive brukere
- 150 oppdrag/mnd
- 50% kommer via peer-to-peer
- NPS >40

---

## FASE 3: Optimalisering (Måned 10-12)
**Mål:** Oppnå bærekraftig drift, dokumentere learnings

**Leveranser:**
- AI-drevet matching (maskinlæring)
- Avansert analytics-dashboard
- Koordinator-manual (replikere til andre bydeler)
- Impact-rapport (white paper)

**Team:**
- Kaja (koordinator) - 50% (ambassadører tar over mye)
- Data scientist (konsulent) - 60 timer
- Forfatter (rapport) - 30 timer

**Budsjett:** 200.000 NOK

**Suksesskriterier:**
- 300 aktive brukere
- 200 oppdrag/mnd
- 70% retention etter 6 mnd
- Klart til å skalere til andre bydeler

---

# KONKLUSJON

**Lokalhjerte** transformerer frivillighet fra:
- ❌ "Uklar, skremmende, forpliktende"
- ✅ "Konkret, enkel, meningsfull"

Ved å kombinere:
1. **Personlig matching** (kompetanse + tid)
2. **Lav terskel** (mikro-oppdrag)
3. **Digital automatisering** (frigjør koordinator)
4. **Menneskelig touch** (Kaja + ambassadører)
5. **Kontinuerlig anerkjennelse** (takk + impact)

...skaper vi en tjeneste som:
- Gjør det lett å si JA
- Trygt å si NEI
- Verdt å si JA IGJEN

**Resultat:**
💚 Dobler antall frivillige uten å ansette flere koordinatorer
💚 Frivillige føler mestring, mening og fellesskap
💚 Bydel Østensjø får 300+ timer frivillig arbeid/mnd
💚 Modellen kan skaleres til andre bydeler i Oslo

> "Lokalhjerte gjør det like enkelt å hjelpe naboen din som å bestille middag på Foodora."
