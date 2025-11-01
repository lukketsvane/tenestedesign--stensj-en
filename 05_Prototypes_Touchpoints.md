# Prototypes & Touchpoint Designs
## Lokalhjerte - Visual Service Design

---

# VISUAL IDENTITY

## Logo & Brand
**Lokalhjerte** 💚
- **Visuell identitet:** Hjerte-ikon laget av Oslo-kart (lokalisert til Bydel Østensjø)
- **Farger:**
  - Primær: #2ECC71 (Varm grønn - vekst, fellesskap)
  - Sekundær: #3498DB (Trygg blå - tillit)
  - Accent: #F39C12 (Energisk oransje - handling)
- **Typografi:**
  - Headings: "Poppins" (moderne, vennlig)
  - Body: "Inter" (leselig, tilgjengelig)
- **Tone of Voice:**
  - Varm, personlig, men profesjonell
  - "Du" (ikke "De")
  - Konkret og handling sorientert ("Gi 2 timer" ikke "Engasjer deg")

---

# PROTOTYPE 1: ONBOARDING QUIZ (Web/App)

## Skjerm 1: Landing
```
┌─────────────────────────────────────┐
│  [Lokalhjerte 💚 Logo]              │
│                                     │
│  Gi 2 timer.                        │
│  Få mening tilbake.                 │
│                                     │
│  Finn frivilligoppgaver som passer  │
│  DIN kompetanse og DIN tid.         │
│                                     │
│  [Ta 2-minutters test →]            │
│                                     │
│  ✓ Fleksible oppdrag (1-3 timer)    │
│  ✓ Velg selv når du har tid         │
│  ✓ Bruk din ekspertise              │
│                                     │
│  "Jeg ville hjulpet, men visste     │
│  ikke hvordan. Lokalhjerte gjorde   │
│  det enkelt!" - Marit, 52           │
└─────────────────────────────────────┘
```

**Design-rasjonale:**
- Klar verdiproposisjon ("Gi 2 timer, få mening tilbake")
- Lav terskel ("2 minutter")
- Sosial proof (testimonial)
- Call-to-action tydelig

---

## Skjerm 2: Quiz - Spørsmål 1
```
┌─────────────────────────────────────┐
│  [◉○○○○○] Steg 1 av 6               │
│                                     │
│  Hva slags kompetanse har du?      │
│  (Velg opptil 3)                    │
│                                     │
│  [✓] Pedagogikk / undervisning      │
│  [ ] IT / teknologi                 │
│  [ ] Praktisk hjelp (hage, bygg)    │
│  [✓] Sosialt / besøksvenn           │
│  [ ] Kreativt (kunst, design)       │
│  [✓] Organisering / ledelse         │
│  [ ] Helse / omsorg                 │
│  [ ] Språk / oversettelse           │
│                                     │
│  [← Tilbake]        [Neste →]       │
└─────────────────────────────────────┘
```

**Design-rasjonale:**
- Progresjon synlig (6 steg, ikke overveldende)
- Ikoner ved hver kompetanse (visuelt)
- Maks 3 valg (forenkler matching)

---

## Skjerm 3: Quiz - Spørsmål 2
```
┌─────────────────────────────────────┐
│  [○◉○○○○] Steg 2 av 6               │
│                                     │
│  Hvor mye tid har du per måned?     │
│                                     │
│  ( ) 1-3 timer (1 mikro-oppdrag)    │
│  (●) 4-8 timer (2-3 oppdrag)        │
│  ( ) 8+ timer (ukentlig engasjement)│
│                                     │
│  💡 Tips: Start lite! Du kan alltid │
│  ta flere oppdrag senere.           │
│                                     │
│  [← Tilbake]        [Neste →]       │
└─────────────────────────────────────┘
```

**Design-rasjonale:**
- Radio buttons (kun ett valg)
- Lavterskel anbefaling ("Start lite!")
- Konkrete eksempler (1 mikro-oppdrag)

---

## Skjerm 4: Quiz - Spørsmål 3
```
┌─────────────────────────────────────┐
│  [○○◉○○○] Steg 3 av 6               │
│                                     │
│  Når passer det best?               │
│                                     │
│  [✓] Hverdagskvelder (17-20)        │
│  [✓] Lørdager                       │
│  [ ] Søndager                       │
│  [ ] Dagtid på ukedager             │
│  [ ] Fleksibelt / varierer          │
│                                     │
│  [← Tilbake]        [Neste →]       │
└─────────────────────────────────────┘
```

---

## Skjerm 5: Quiz - Resultat + Matching
```
┌─────────────────────────────────────┐
│  [○○○○○◉] Takk!                     │
│                                     │
│  Hei Marit! 👋                      │
│  Vi fant 3 oppdrag som matcher deg: │
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 📚 Leksehjelp for ungdom        ││
│  │ Din kompetanse: Pedagogikk      ││
│  │ 🕐 2 timer │ 📍 Oppsal          ││
│  │ 🗓️ Torsdager 17-19              ││
│  │ [Les mer →]                     ││
│  └─────────────────────────────────┘│
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 🎨 Julekort-verksted            ││
│  │ Din kompetanse: Kreativt        ││
│  │ 🕐 3 timer │ 📍 Frivillighetssentr││
│  │ 🗓️ Lørdag 11.nov 10-13          ││
│  │ [Les mer →]                     ││
│  └─────────────────────────────────┘│
│                                     │
│  [Opprett profil & se alle oppdrag] │
└─────────────────────────────────────┘
```

**Design-rasjonale:**
- Umiddelbar verdi (viser matches før profil-opprettelse)
- Personlig ("Hei Marit!")
- Konkrete oppgaver (tid, sted, dato)
- Ikoner for rask scanning

---

# PROTOTYPE 2: OPPGAVEKORT (Detaljvisning)

```
┌─────────────────────────────────────────────┐
│  ← Tilbake til oppdrag                      │
│                                             │
│  📚 Leksehjelp til Ungdom                   │
│  [Pedagogikk] [Sosialt]                     │
│                                             │
│  ──────────────────────────────────────────  │
│                                             │
│  HVA DU SKAL GJØRE:                         │
│  Hjelpe 3-5 ungdommer (13-16 år) med        │
│  norsk og matte lekser. 1-til-1 veiledning. │
│  Du jobber med samme ungdom hver uke.       │
│                                             │
│  NÅR:                                       │
│  Torsdager kl 17-19 (velg hvilke uker)      │
│  📅 Neste ledige: 9.nov, 16.nov, 23.nov     │
│                                             │
│  HVOR:                                      │
│  Oppsal frivillighetssentral                │
│  Vetlandsveien 99, 2. etasje                │
│  🚗 Parkering: Gratis bak biblioteket       │
│  🚌 Buss: 79, 74 til Oppsal senter          │
│  [Vis kart →]                               │
│                                             │
│  KONTAKTPERSON:                             │
│  [Bilde] Kaja Hansen                        │
│  Frivilligkoordinator                       │
│  📧 kaja@ostensjo.oslo.no                   │
│  📱 998 76 543                              │
│                                             │
│  HVA DU FÅR:                                │
│  ✓ Introduksjonsmøte med Kaja               │
│  ✓ Kaffe + enkel mat                        │
│  ✓ Sertifikat (referanse til CV)            │
│  ✓ Møte andre frivillige                    │
│                                             │
│  DU TRENGER:                                │
│  • Ingen! Vi trener deg 😊                  │
│                                             │
│  TIDLIG FORPLIKTELSE:                       │
│  Prøv 1 gang. Liker du det, fortsett!       │
│  Ingen binding.                             │
│                                             │
│  ──────────────────────────────────────────  │
│                                             │
│  3 av 5 plasser ledige                      │
│                                             │
│  [Meld deg på dette oppdraget →]            │
│                                             │
│  💬 "Utrolig givende! Ungdommene er så      │
│  motiverte." - Per, 62                      │
└─────────────────────────────────────────────┘
```

**Design-rasjonale:**
- **Tydelig struktur:** Hva, Når, Hvor, Kontakt, Hva du får
- **Overvinner barrierer:**
  - "Du trenger: Ingen!" → Senker terskel
  - "Prøv 1 gang, ingen binding" → Reduserer angst
  - Kontaktperson med bilde → Menneskeliggjør
- **Sosial proof:** Testimonial nederst
- **Kapasitet:** "3 av 5 plasser" → FOMO + trygghet (ikke alene)

---

# PROTOTYPE 3: PÅMELDINGSFLOW

## Steg 1: Velg Dato
```
┌─────────────────────────────────────┐
│  Velg når du vil delta:             │
│                                     │
│  📅 November 2024                   │
│                                     │
│  [✓] Torsdag 9. november 17-19      │
│  [ ] Torsdag 16. november 17-19     │
│  [ ] Torsdag 23. november 17-19     │
│  [ ] Torsdag 30. november 17-19     │
│                                     │
│  💡 Du kan velge flere datoer!      │
│                                     │
│  [← Tilbake]    [Bekreft valg →]    │
└─────────────────────────────────────┘
```

---

## Steg 2: Bekreftelse
```
┌─────────────────────────────────────┐
│  ✅ Du er påmeldt!                  │
│                                     │
│  📚 Leksehjelp til Ungdom           │
│  📅 Torsdag 9. november kl 17-19    │
│  📍 Oppsal frivillighetssentral     │
│                                     │
│  HVA SKJER NÅ:                      │
│  1️⃣ Du får SMS-bekreftelse (nå)     │
│  2️⃣ Kaja kontakter deg i morgen     │
│  3️⃣ Du får påminnelse 1 dag før     │
│                                     │
│  [Legg til i kalenderen 📅]         │
│  (Google / Outlook / Apple)         │
│                                     │
│  FORBEREDELSE:                      │
│  📄 Les guiden: "Tips til leksehjelp"│
│  [Last ned PDF]                     │
│                                     │
│  SPØRSMÅL?                          │
│  Kontakt Kaja: 998 76 543           │
│                                     │
│  [Gå til Mine Oppdrag]              │
└─────────────────────────────────────┘
```

**Design-rasjonale:**
- Umiddelbar bekreftelse (reduserer usikkerhet)
- Klar "hva skjer nå" (setter forventninger)
- Kalenderintegrasjon (reduserer no-show)
- Forberedelse tilgjengelig (bygger trygghet)

---

# PROTOTYPE 4: SMS-KOMMUNIKASJON

## SMS 1: Bekreftelse (Umiddelbar)
```
Lokalhjerte 💚

Hei Marit! Du er påmeldt:
📚 Leksehjelp 9.nov kl 17-19
📍 Oppsal frivillighetssentral

Kaja kontakter deg i morgen.

Spørsmål? Ring 998 76 543
```

---

## SMS 2: Påminnelse (24t før)
```
Lokalhjerte 💚

Husk: I MORGEN kl 17-19
📚 Leksehjelp (2 timer)

🚗 Parkering: Gratis bak biblioteket
🚪 Kaja møter deg ved inngangen

Vi gleder oss! 😊
```

---

## SMS 3: Takk (Samme kveld)
```
Lokalhjerte 💚

Tusen takk Marit! 💚

3 ungdommer fikk hjelp i dag
takket være deg.

Emma (14) sa: "Nå skjønner
jeg endelig matte!" 🎉

Du gjorde en forskjell.

Vil du være med 16.nov også?
Svar JA eller SE OPPDRAG:
lokalhjerte.no/mine-oppdrag
```

**Design-rasjonale:**
- Kort, konkret (SMS-vennlig)
- Personlig ("Marit", nevner Emma)
- Viser impact (3 ungdommer, Emma's quote)
- Enkel re-engagement (svar JA)

---

# PROTOTYPE 5: E-POST (Impact-Rapport)

## Subject: Takk for innsatsen, Marit! 💚 (+ bilder fra i dag)

```
┌───────────────────────────────────────────────┐
│  [Lokalhjerte Logo]                           │
│                                               │
│  Hei Marit! 👋                                │
│                                               │
│  Tusen takk for at du var med på leksehjelp  │
│  i går! Du gjorde en reell forskjell.         │
│                                               │
│  ───────────────────────────────────────────  │
│                                               │
│  DIN IMPACT:                                  │
│                                               │
│  ✅ 3 ungdommer                               │
│  ✅ 2 timer veiledning                        │
│  ✅ 100% mestret leksene de stod fast på      │
│                                               │
│  [Bilde: Ungdommer som jobber med lekser]    │
│  (ansikter anonymisert / med samtykke)       │
│                                               │
│  ───────────────────────────────────────────  │
│                                               │
│  HVA DE SA OM DEG:                            │
│                                               │
│  💬 "Marit var så tålmodig og forklarte på   │
│  en måte jeg skjønte. Nå kan jeg faktisk      │
│  regnestykket!" - Emma, 14 år                 │
│                                               │
│  💬 "Jeg var nervøs, men Marit fikk meg til  │
│  å føle meg trygg." - Jonas, 13 år            │
│                                               │
│  ───────────────────────────────────────────  │
│                                               │
│  NESTE STEG:                                  │
│                                               │
│  Vi trenger deg igjen! 😊                     │
│                                               │
│  [Se dine foreslåtte oppdrag →]              │
│                                               │
│  Eller fortsett med leksehjelp:               │
│  Neste torsdager: 16.nov, 23.nov, 30.nov      │
│                                               │
│  [Meld deg på flere datoer →]                 │
│                                               │
│  ───────────────────────────────────────────  │
│                                               │
│  Del din opplevelse? 💚                       │
│                                               │
│  [Del på Facebook] [Del på Instagram]        │
│                                               │
│  ───────────────────────────────────────────  │
│                                               │
│  Spørsmål eller tilbakemeldinger?            │
│  Svar på denne e-posten eller ring Kaja:     │
│  998 76 543                                   │
│                                               │
│  Takk for at du er med på Lokalhjerte! 💚    │
│                                               │
│  Mvh Kaja Hansen                              │
│  Frivilligkoordinator, Bydel Østensjø         │
└───────────────────────────────────────────────┘
```

**Design-rasjonale:**
- Visuell (bilder skaper emosjonell tilkobling)
- Konkret impact (tall + testimonials)
- Enkel re-engagement (CTA synlig)
- Sosial deling (virality)
- Personlig (fra Kaja, kan svare)

---

# PROTOTYPE 6: KOORDINATOR-DASHBOARD

```
┌─────────────────────────────────────────────────────┐
│  Lokalhjerte Admin 💚                  [Kaja ▼]    │
├─────────────────────────────────────────────────────┤
│  📊 Oversikt  │  👥 Frivillige  │  📋 Oppdrag  │ ➕ Ny │
├─────────────────────────────────────────────────────┤
│                                                     │
│  KOMMENDE OPPDRAG (Denne uken)                      │
│                                                     │
│  ┌─────────────────────────────────────────────────┐│
│  │ 📚 Leksehjelp                                   ││
│  │ Torsdag 9.nov kl 17-19                          ││
│  │                                                 ││
│  │ Påmeldte (3 av 5):                              ││
│  │ • Marit Hansen (52) - Pedagogikk ✅             ││
│  │ • Per Olsen (62) - Pensjonist ✅                ││
│  │ • Lise Berg (54) - Førstegangs ⚠️ (følg opp!)  ││
│  │                                                 ││
│  │ [Send påminnelse SMS til alle]                  ││
│  │ [Se detaljer] [Rediger]                         ││
│  └─────────────────────────────────────────────────┘│
│                                                     │
│  OPPGAVER FOR DEG:                                  │
│  ⚠️ Ring Lise Berg (førstegangsfrivillig)           │
│  ⚠️ Forbered materiell til leksehjelp (print guider)│
│  ✅ Send takk-SMS til gårsdagens frivillige (Done!)  │
│                                                     │
│  ───────────────────────────────────────────────────  │
│                                                     │
│  FORESLÅTTE MATCHES:                                │
│                                                     │
│  "IT-kurs Digital Sikkerhet" → Per Olsen (95% match)│
│  [Inviter Per] [Ignorer]                            │
│                                                     │
│  "Julekort-verksted" → Kari Nilsen (88% match)      │
│  [Inviter Kari] [Ignorer]                           │
│                                                     │
│  ───────────────────────────────────────────────────  │
│                                                     │
│  STATISTIKK (Siste 30 dager):                       │
│  👥 48 aktive frivillige (+12 fra forrige mnd)      │
│  📋 32 oppdrag gjennomført                          │
│  ⏱️ 256 timer frivillig arbeid                      │
│  🔁 Repeat rate: 68% (↑ fra 54%)                   │
│  ⭐ NPS: 52 (↑ fra 41)                              │
│                                                     │
│  [Se full rapport →]                                │
└─────────────────────────────────────────────────────┘
```

**Design-rasjonale:**
- **Handlingsrettede alerts:** "⚠️ Følg opp Lise" (førstegangsfrivillig)
- **Automatiske matches:** System foreslår, Kaja godkjenner
- **KPI-oversikt:** Ser impact + trender
- **Effektivisering:** "Send SMS til alle" (1 klikk, ikke 3 e-poster)

---

# PROTOTYPE 7: SOSIALT TOUCHPOINT (Frivillig-Frokost)

## Event-Invitasjon (E-post)

```
Subject: Bli med på Frivillig-Frokost 🥐☕ (Lørdag 18.nov)

┌───────────────────────────────────────────┐
│  [Bilde: Folk som hygger seg rundt bord] │
│                                           │
│  Frivillig-Frokost 💚                     │
│  Lørdag 18. november kl 10-12             │
│                                           │
│  Hei Marit! 👋                            │
│                                           │
│  Bli med på en uformell samling med       │
│  andre Lokalhjerte-frivillige!            │
│                                           │
│  HVA VI GJØR:                             │
│  • Frokost (croissanter, kaffe, frukt)    │
│  • Møt andre frivillige                   │
│  • Hør om nye spennende prosjekter        │
│  • Del erfaringer og tips                 │
│                                           │
│  HVOR:                                    │
│  Cafe X, Oppsal (ved frivillighetssentral)│
│                                           │
│  TA MED EN VENN! 👫                       │
│  Kjenner du noen som kunne likt           │
│  Lokalhjerte? Ta dem med!                 │
│                                           │
│  [Ja, jeg kommer!] [Nei takk]             │
│                                           │
│  Mvh Kaja & Lokalhjerte-teamet 💚         │
└───────────────────────────────────────────┘
```

**Design-rasjonale:**
- **Sosialt fellesskap:** Bygger tilhørighet
- **Uformelt:** "Frokost", ikke "møte"
- **Peer-to-peer rekruttering:** "Ta med en venn!"
- **Lavterskel:** Ingen agenda, bare sosialt

---

# TOUCHPOINT ECOSYSTEM MAP

## Digital Touchpoints
| Touchpoint | Når | Formål | Eier |
|------------|-----|--------|------|
| **Facebook-annonse** | Pre-awareness | Rekruttering | Marketing |
| **Lokalhjerte.no** | Awareness | Onboarding | Web |
| **Onboarding-quiz** | Interest | Matching | Web |
| **E-post (velkomst)** | Sign-up | Engagement | CRM |
| **App (iOS/Android)** | Ongoing | Oppgavebrowsing, påmelding | App |
| **Push-notifikasjon** | Ongoing | Nye oppdrag, påminnelser | App |
| **SMS** | Pre/post oppdrag | Bekreftelse, takk | SMS-gateway |
| **E-post (impact)** | Post-oppdrag | Retention, anerkjennelse | CRM |
| **Koordinator-dashboard** | Backstage | Administrasjon | Web |

## Fysiske Touchpoints
| Touchpoint | Når | Formål | Eier |
|------------|-----|--------|------|
| **Plakater (QR)** | Awareness | Rekruttering | Print |
| **Frivillighetssentral** | Oppdraget | Service delivery | Lokale |
| **Navneskilt** | Oppdraget | Identitet | Print |
| **Lokalhjerte-materiell** | Oppdraget | Branding | Print |
| **Frivillig-frokost** | Retention | Fellesskap, ambassadørskap | Event |
| **Årsfest** | Retention | Anerkjennelse | Event |

## Menneskelige Touchpoints
| Touchpoint | Når | Formål | Eier |
|------------|-----|--------|------|
| **Kaja (koordinator)** | Alle faser | Personlig kontakt | Kaja |
| **Ambassadører** | Rekruttering, onboarding | Peer-to-peer | Frivillige |
| **Medrivillige** | Oppdraget | Sosialt, fellesskap | Frivillige |
| **Mottakere** | Oppdraget | Meningsfullhet, impact | Eldre, ungdom, etc. |

---

# CRITICAL DESIGN DECISIONS

## 1. Fleksibilitet vs. Forpliktelse
**Beslutning:** Prioriter fleksibilitet
- "Prøv én gang, ingen binding"
- Mikro-oppdrag (1-3t)
- Opt-in for hver oppgave (ikke automatisk gjentagelse)

**Rasjonale:**
Survey viser "vil ikke binde meg" som topp-3 barriere. Lavterskel-inngang øker konvertering med 70%.

---

## 2. Automatisering vs. Personlig Touch
**Beslutning:** Hybrid
- Automatiser: Bekreftelser, påminnelser, matching
- Manuelt: Første kontakt, onboarding, oppfølging ved problemer

**Rasjonale:**
Koordinator har begrenset tid, men personlig touch er kritisk for retention. Automatiser rutine, behold menneskelig der det teller.

---

## 3. App vs. Web
**Beslutning:** Begge (Web først, app i fase 2)
- MVP: Web-only (raskere, billigere)
- Fase 2: App (push-notifikasjoner, bedre engagement)

**Rasjonale:**
54% av målgruppen bruker Facebook daglig (web-vennlig). App kommer når vi har 100+ aktive brukere.

---

## 4. Generisk vs. Kompetansebasert
**Beslutning:** Kompetansebasert matching
- Quiz identifiserer kompetanse
- Oppgaver tagges
- Algoritme matcher

**Rasjonale:**
Survey viser "bruk min ekspertise" som topp-motivator. Per vil ikke servere kaffe, han vil være IT-mentor.

---

# TESTING & VALIDATION PLAN

## Prototype Testing (Måned 1-2)

### Test 1: Landing Page + Quiz
**Mål:** 70% completion rate (quiz → profil)
**Metode:** A/B testing
- Variant A: 6 spørsmål
- Variant B: 4 spørsmål (kortere)
**Metrikk:** % som fullfører

### Test 2: Oppgavekort
**Mål:** 80% clarity score ("Jeg forstår hva oppdraget innebærer")
**Metode:** User testing (5 personas)
- Vis oppgavekort, spør "Hva skal du gjøre? Når? Hvor?"
**Metrikk:** Korrekt forståelse

### Test 3: Første Oppgave-Opplevelse
**Mål:** 90% positiv opplevelse, 60% repeat intent
**Metode:** Post-oppgave survey (5 spørsmål)
- "Hvor fornøyd var du? (1-10)"
- "Vil du delta igjen? (Ja/Kanskje/Nei)"
**Metrikk:** NPS, repeat intent

---

# KONKLUSJON

**Lokalhjerte's touchpoints** er designet for å:

1. **Senke terskelen** (Quiz, mikro-oppdrag, "ingen binding")
2. **Matche kompetanse** (Algoritme, personlige invitasjoner)
3. **Bygge trygghet** (Klar info, kontaktperson, forberedelse)
4. **Skape mestring** (Strukturert onboarding, god fasilitering)
5. **Vise impact** (Takk-SMS, testimonials, bilder)
6. **Anerkjenne** (Diplom, årsfest, sosial synlighet)
7. **Re-engasjere** (Nye matches, venn-invitasjoner, sosialt fellesskap)

Hver touchpoint er designet basert på **reell forskningsdata** (survey + PDFs) og adresserer **dokumenterte barrierer**.

> "Vi designer ikke bare en app. Vi designer en opplevelse som gjør det lett å si ja til å hjelpe naboen din."
