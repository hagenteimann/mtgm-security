# Projekt-Brief – MTGM Sicherheitsdienst Rebrand

## Phase 0: Brief ausfüllen

### 0.1 – Alte Website analysieren

```
ALTE WEBSITE
─────────────────────────────────────────────
URL / Dateipfad: https://www.mtgm-sicherheit.de/
Primäre Schwächen:
  - [x] Kein klarer CTA (Kontaktformular schwer zu finden/nutzen)
  - [x] Veraltetes Layout (Jimdo-Standard-Template)
  - [x] Schlechte Mobile-Darstellung (Funktional, aber nicht "premium")
  - [x] Unklare Zielgruppenansprache (Sehr textlastig, wenig visuelle Führung)
  - [x] Zu langsam (Performance)
  - [x] Sonstiges: Logo im Hero "reingebastelt", ungleichmäßige Abstände.

Was funktioniert / behalten:
  - Farbe/Branding: Blau als Akzentfarbe, Spartan-Helm als Symbol.
  - Vertrauenselemente: Geschichte des Gründers (Weltmeister Kickboxen), Fokus auf Psychologie/Deeskalation.
  - Inhalte die gut performen: Klare Auflistung der Leistungen (Objektschutz, Veranstaltungsschutz).

Vorhandene Farbcodes:
  Primär (Blau): #2e79b9
  Sekundär (Dunkelgrau): #333333
  Hintergrund: #FFFFFF
  Akzent (Rot): Optional (aus Krawatte des Gründers ableitbar für Signal-CTAs)
```

### 0.2 – Zielgruppe ableiten

```
ZIELGRUPPE
─────────────────────────────────────────────
Persona (kurz): Geschäftskunden, Kommunen, Event-Veranstalter.
Alter / technische Affinität: 30-60 Jahre, mittlere technische Affinität.
Entscheidungstreiber (sortiert nach Priorität):
  1. Zuverlässigkeit & Professionalität (Sicherheit ist Vertrauenssache).
  2. Kompetenz (Deeskalations-Expertise).
  3. Lokale Präsenz (Bodenseeregion).
Primäres Gerät: [ ] Desktop  [ ] Mobile  [x] Beides
Sprache / Ton der Ansprache: [x] Sachlich  [ ] Emotional  [x] Premium  [ ] Locker
Größter Einwand vor dem Kauf/Kontakt: "Ist das ein seriöses Unternehmen oder nur eine 'Türsteher-Truppe'?"
```

### 0.3 – Design-Entscheidungen ableiten

```
ABGELEITETE DESIGN-ENTSCHEIDUNGEN
─────────────────────────────────────────────
Primärfarbe (begründet):
  Farbe: #1a365d (Deep Navy Blue) oder #2e79b9 (Aktuelles Blau, aber modernisiert)
  Grund: Blau steht für Vertrauen, Sicherheit und Seriosität. Ein tieferes Blau wirkt "premium".

Ton / Bildsprache:
  Clean, seriös, "High-End Security". Keine martialischen Bilder, sondern Fokus auf Präsenz und Deeskalation.
  Spartan-Helm als hochwertiges Vektorgrafik-Element einbinden.

Above-the-Fold-Ziel (was muss sofort sichtbar sein):
  Professionelles Erscheinungsbild, USP (Deeskalation & Kompetenz), direkter Weg zur Anfrage.

Primärer CTA (Text + Ziel):
  "Kostenloses Erstgespräch vereinbaren" -> Kontakt/Formular.

Wichtigste Vertrauenselemente:
  - "Weltmeister-Expertise" (Disziplin).
  - Leistungen auf einen Blick.
  - Testimonials/Referenzen (wenn vorhanden).

Sektionen-Reihenfolge (Entwurf):
  1. Hero (Vertrauen + CTA)
  2. Leistungen (Kompakte Cards - Schnell erfassbar)
  3. Bilder-Galerie (Bento Grid - Visueller Anker)
  4. Warum MTGM? (Psychologie & Deeskalation)
  5. Über uns (Gründer-Story)
  6. Referenzen/Vertrauen
  7. Kontakt (Funnel-Abschluss)

Layout-Regeln:
  - Bento Boxen EXKLUSIV für Bildergalerien.
  - Dienstleistungen & Text-Inhalte IMMER in kompakten Cards (schnelle Erfassbarkeit).
```

### 0.4 – Relevante Guides festlegen

```
GUIDES FÜR DIESES PROJEKT
─────────────────────────────────────────────
[x] DESIGN_SYSTEM.md        – immer
[x] FUNNEL_STRATEGIE.md     – Conversion-Ziel "Anfrage"
[x] CONTENT_GUIDELINES.md   – Tone of Voice schärfen
[ ] SEO.md                  
[ ] ACCESSIBILITY_TESTING.md 
[x] WORKFLOW_NAVIGATION.md  
```

---

## Phase 1: Token-Mapping

```css
:root {
  /* Primary: Modernized Trust Blue */
  --color-primary-300: #1e4e8c; 
  --color-primary-400: #163a69;

  /* Neutrals for Premium Look */
  --color-neutral-900: #0f172a; /* Slate Dark */
  --color-neutral-100: #f1f5f9;

  /* Accents */
  --color-accent-red: #e11d48; /* For urgent CTAs */

  /* Spacing & Radius */
  --space-unit: 8px;
  --radius-base: 12px;
  --radius-subtle: 8px;
}
```
