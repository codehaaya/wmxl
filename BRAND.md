# Warung Mini XL — Merk- & stijlboek

> *Een stukje Suriname in Nederland.*

Dit boek legt de visuele en verbale identiteit van Warung Mini XL vast. Eén
systeem, consequent toegepast op de hele website. De live stijlgids staat op de
site zelf onder **#merkboek**.

---

## 1. Merkkern

**Positionering:** authentieke Surinaams-Javaanse keuken, dagvers bereid volgens
oma's recepten — afhalen of bezorgen vanuit Den Haag, Rijswijk en Berkel & Rodenrijs.

**Merkwaarden:** Authentiek · Familie · Dagvers · Gastvrij · Trots Surinaams-Javaans

---

## 2. Logo

Het logo bestaat uit het **warung-huisje met bestek** (beeldmerk) en het
**brush-woordmerk** "Warung Mini XL" met de tagline *Surinaams-Javaanse specialiteiten*.

- **Primair logo** — beeldmerk + woordmerk + tagline, op lichte achtergrond.
- **Donkere variant** — wit woordmerk op inkt/donkere vlakken (footer).
- **Beeldmerk los** — het oranje huisje, voor favicons, avatars, kleine plekken.

**Regels**
- Houd minimaal de hoogte van het dak als **vrije ruimte** rondom het logo.
- **Minimale maat:** woordmerk ≥ 120 px breed (beeldmerk ≥ 28 px).
- **Niet doen:** uitrekken, verkleuren, draaien, of op te lage contrast plaatsen.

> De live recreatie staat in `src/components/Logo.tsx`. Plaats je officiële
> bestand als `public/logo.svg` of `public/logo.png` en het wordt automatisch
> overgenomen.

---

## 3. Kleuren

| Rol | Naam | Token | Hex |
|---|---|---|---|
| Primair | Warung Oranje | `--chili` | `#ff4d08` |
| Primair | Oranje Diep | `--chili-dark` | `#db3d00` |
| Primair | Oranje Zacht | `--chili-soft` | `#ffe6d9` |
| Accent | Amber | `--turmeric` | `#ff9200` |
| Accent | Amber Diep | `--turmeric-deep` | `#e06f00` |
| Accent | Amber Zacht | `--turmeric-soft` | `#fff0dd` |
| Functioneel | Blad Groen | `--leaf` | `#2e7d5b` |
| Functioneel | Groen Zacht | `--leaf-soft` | `#e2f0e8` |
| Neutraal | Inkt | `--ink` | `#201712` |
| Neutraal | Inkt Zacht | `--ink-soft` | `#4f433b` |
| Neutraal | Muted | `--muted` | `#8a7c72` |
| Neutraal | Lijn | `--line` | `#f1e2d6` |
| Neutraal | Zand | `--sand` | `#f6ddca` |
| Oppervlak | Crème | `--cream` | `#fff8f3` |
| Oppervlak | Crème 2 | `--cream-2` | `#ffeee3` |
| Oppervlak | Surface | `--surface` | `#ffffff` |

Oranje is voor actie en energie; groen uitsluitend functioneel (vega/succes);
neutralen houden alles leesbaar en warm.

---

## 4. Typografie

| Rol | Lettertype | Gebruik |
|---|---|---|
| Koppen | **Montserrat** (700–900) | Titels, vaak uppercase — in de geest van *Lemon Milk*. |
| Tekst | **Open Sans** (400–700) | Alle lopende tekst en UI. |
| Woordmerk | **Pacifico** (brush) | Uitsluitend logo en spaarzame hero-accenten. |

**Typeschaal:** Hero (Montserrat 900, uppercase) → Sectiekop H2 (800, uppercase)
→ Gerechtnaam H4 (800, normale case) → Eyebrow (Open Sans 700, uppercase, +14%
letterafstand) → Lopende tekst (Open Sans 400, 1.55 regelhoogte).

---

## 5. Iconografie & food tiles

Geen stockfoto's: gerechten worden getoond als **emoji-tegels** met
categoriespecifieke oranje/perzik-gradients. Snel, schaalbaar, copyrightvrij en
altijd on-brand. Labels: Populair, Chef's choice, Vega/Vegan, Pittig, Halal.
Pittigheid wordt aangegeven met 🌶️-pips (0–3).

---

## 6. Componenten

Knoppen (primair oranje met gloed, ghost, donker), chips & filters, het
afhalen/bezorgen-segment, hoeveelheid-steppers en de productkaart zijn allemaal
opgebouwd uit dezelfde tokens. Zie de live voorbeelden in de stijlgids.

---

## 7. Tone of voice

We praten zoals we koken: **warm, eerlijk en trots**.

- **Wel:** warm & persoonlijk · eerlijk & concreet · Nederlands-eerst · trots op de roots.
- **Niet:** afstandelijk/corporate · overdreven/vaag · onnodig Engels · de afkomst wegpoetsen.

Woorden die bij ons passen: *dagvers · oma's recept · een stukje Suriname · met liefde · echt · huisgemaakt*.

---

## 8. Vormgeving

- **Radius:** sm 10 · md 16 · lg 22 · xl 30 · pill 999 px.
- **Schaduw:** zacht en warm getint; oranje gloed onder primaire knoppen.
- **Ritme:** ruime sectiepadding, container max. 1180 px.

---

*Warung Mini XL — Merk- & stijlboek v1.0 · Bereid met liefde in Den Haag.*
