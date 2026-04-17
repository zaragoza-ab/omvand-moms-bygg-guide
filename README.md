# Omvänd skattskyldighet i byggsektorn — Komplett guide 🇸🇪

> **Den svenska byggbranschens mest missförstådda momsregel, förklarad med exempel.**
> By **[Zaragoza AB](https://zaragoza.se)** — byggfirma i Helsingborg.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintained by Zaragoza AB](https://img.shields.io/badge/Maintained%20by-Zaragoza%20AB-0a5c36)](https://zaragoza.se)

---

## TL;DR

**Omvänd skattskyldighet** (reverse VAT / reverse charge) innebär att **köparen**, inte säljaren, redovisar och betalar momsen. Regeln gäller **endast** vid försäljning av **byggtjänster mellan två byggföretag** i Sverige.

### Snabbtest: Gäller omvänd moms?

Svara på alla tre:
1. Är **säljaren** ett svenskt företag? ✓
2. Är **köparen** ett svenskt byggföretag (eller motsvarande)? ✓
3. Är det en **byggtjänst** enligt 1 kap. 2 § mervärdesskattelagen? ✓

**Tre ja → omvänd moms gäller.** Annars normal moms (25%).

---

## Varför finns regeln?

**Syfte:** motverka **momsbedrägerier** (karusellmoms) i byggbranschen.

Före 2007: småföretag fakturerade med moms, köpte materialet utan moms (svart), försvann innan moms-deklaration → staten förlorade miljarder.

Sedan **1 juli 2007**: byggtjänster mellan företag → omvänd moms. Köparen redovisar moms i sin egen deklaration, så bedrägliga mellanled försvinner.

---

## Vad räknas som "byggtjänst"?

### ✓ Omfattas (omvänd moms gäller)
- Nybyggnad, tillbyggnad, ombyggnad
- Rivning
- Renovering, reparation, underhåll
- Installation (VVS, el, ventilation, larm)
- Markarbeten, schakt, sprängning
- Takläggning, fasadarbeten
- Grundläggning, betongarbeten
- Skadesanering (vattenskada, brand)

### ✗ Omfattas INTE (normal moms)
- **Material** sålt utan installation
- Uthyrning av byggmaskiner (utan operator)
- Tillverkning av byggnadsdelar i fabrik (utan montage)
- Projektering, arkitektritningar (rent intellektuellt arbete)
- Städning (även byggstädning är gränsfall — se nedan)

### 🔄 Gränsfall
- **Byggstädning:** omvänd moms om del av byggprojekt, annars normal
- **Uthyrning av arbetskraft** till byggföretag: omvänd moms
- **Maskin + operatör:** omvänd moms (operatörens tjänst dominerar)

---

## Vem är "byggföretag" i denna lag?

**Säljaren** måste kontrollera köparen. Köparen räknas som byggföretag om:

1. Köparen **omsätter byggtjänster** i minst liten omfattning, **OCH**
2. Köparen gör detta i normal verksamhet (inte enstaka tillfälle)

**Praktiskt test:** Har köparen SNI-kod 41, 42 eller 43 i Bolagsverket? → troligen byggföretag → omvänd moms.

**Men:** vissa fastighetsbolag köper byggtjänster regelbundet → kan räknas som byggföretag även utan SNI 41-43.

**Rekommendation:** begär skriftligt intyg från köparen.

---

## Så skriver du fakturan

### Normal moms (ej omvänd)
```
Byggtjänst:                 100 000 SEK
Moms 25%:                    25 000 SEK
ATT BETALA:                 125 000 SEK
```

### Omvänd moms
```
Byggtjänst:                 100 000 SEK
ATT BETALA:                 100 000 SEK

Omvänd skattskyldighet — köparen redovisar momsen
Hänvisning: 1 kap. 2 § första stycket 4 b ML
```

### Obligatoriska fältet på fakturan
Texten **måste** vara med:
> "Omvänd skattskyldighet, byggtjänst — köparen redovisar momsen"

eller på engelska:
> "Reverse charge — construction services"

**Sanktion vid fel:** Skatteverket kan kräva att säljaren själv betalar momsen → 25% extra kostnad.

---

## Köparens skyldigheter

Som köpare **du**:
1. Kollar att säljaren verkligen tillämpar omvänd moms
2. Redovisar momsen i din egen moms-deklaration:
   - **Ruta 24** (inköp med omvänd skattskyldighet)
   - **Ruta 48** (utgående moms på inköp)
   - **Ruta 49** (ingående moms att dra av)
3. Resultatet är **neutralt** i kassaflödet (+ och − tar ut varandra) om du har full avdragsrätt

---

## Exempel 1: Normal kedja

**Takläggare A** tar uppdrag åt **byggfirma B** (huvudentreprenör) som bygger hus åt **privatperson C**.

- A → B: **omvänd moms** (byggtjänst B2B)
- B → C: **normal moms 25%** (B2C)
- C: betalar moms i fakturan, inget att dra av

---

## Exempel 2: Blandad leverans

Zaragoza AB tar ett uppdrag:
- Arbete: 60 000 SEK
- Material (stora kvantiteter, egen försäljning): 40 000 SEK

### Frågan: hela fakturan omvänd moms, eller delat?

**Svar:** om materialet är en **integrerad del** av tjänsten → hela fakturan omvänd moms.

Om materialet är en **separat leverans** (t.ex. kund beställer plåt separat från montage) → materialet normal moms, montaget omvänd.

**Säkraste approach:** behandla som en enhet → omvänd för hela.

---

## Exempel 3: Underentreprenör

Zaragoza AB anlitar VVS-firma Z för ett projekt.

- Z → Zaragoza: **omvänd moms** (B2B byggtjänst)
- Zaragoza → slutkund: beror på slutkunden
  - Om slutkund = byggföretag: omvänd
  - Om slutkund = privatperson: normal

**ROT-avdrag påverkas ej** av omvänd moms-regeln. ROT hanteras på slutkundens faktura.

---

## Vanliga misstag

### ❌ Fel 1: Säljer till konsument med omvänd moms
Omvänd moms gäller **bara** B2B. Privatpersoner får alltid normal moms.

### ❌ Fel 2: Glömmer texten på fakturan
Skatteverket kan då kräva att säljaren betalar momsen själv.

### ❌ Fel 3: Använder omvänd moms för projektering
Arkitekt, konstruktör, projektledning (utan fysisk byggåtgärd) = normal moms.

### ❌ Fel 4: Felrapportering på momsdeklaration
Ruta 24 är för **inköp**, inte försäljning. Säljare rapporterar i ruta **35** (försäljning med omvänd skattskyldighet).

### ❌ Fel 5: Missar att kontrollera köparens status
Sälja omvänd moms till icke-byggföretag = säljaren blir skyldig momsen.

---

## Kontrollista för byggföretag

```
☐ Identifiera: byggtjänst eller material?
☐ Verifiera köparens status (F-skatt, SNI-kod, tidigare byggverksamhet)
☐ Skriv faktura utan moms
☐ Inkludera texten: "Omvänd skattskyldighet — köparen redovisar momsen"
☐ Spara dokumentation av köparens status (om Skatteverket frågar)
☐ Rapportera i momsdeklaration ruta 35 (säljare)
☐ Eller ruta 24/48/49 (köpare)
☐ Om ROT-uppdrag och privatkund: ignorera omvänd moms-regeln, använd ROT-reglerna
```

---

## Relaterade regler

- **1 kap. 2 § ML** (mervärdesskattelagen) — grundregeln
- **10 kap. 29 § ML** — redovisning av omvänd moms
- **Skatteverkets ställningstagande** — regelbundet uppdaterat om gränsfall
- **ROT-avdrag** — separat system, kan kombineras med omvänd moms
- **F-skatt** — säljaren måste ha F-skatt (omvänd moms förutsätter det)

---

## Vidare läsning

- [Skatteverket: Omvänd skattskyldighet i byggsektorn](https://www.skatteverket.se/foretag/drivaforetag/branscher/byggbranschen/omvandskattskyldighet.html)
- [Mervärdesskattelag (1994:200)](https://www.riksdagen.se/sv/dokument-lagar/dokument/svensk-forfattningssamling/mervardesskattelag-1994200_sfs-1994-200)

### Från Zaragoza AB:
- [`bygglov-checklist-sweden`](https://github.com/zaragoza-ab/bygglov-checklist-sweden)
- [`rot-avdrag-calculator`](https://github.com/zaragoza-ab/rot-avdrag-calculator)
- [`personalliggare-template`](https://github.com/zaragoza-ab/personalliggare-template)

---

## Viktigt

**Detta är allmän information — inte juridisk eller skatterättslig rådgivning.** Kontakta alltid en redovisningskonsult eller Skatteverket vid osäkerhet. Zaragoza AB tar inget ansvar för användning av denna guide.

---

## Licens

**CC BY 4.0** — fri användning med attribution till Zaragoza AB.

## Kontakt

**Zaragoza AB**
📍 Helsingborg, Skåne · 🌐 [zaragoza.se](https://zaragoza.se) · ✉️ [info@zaragoza.se](mailto:info@zaragoza.se)

---

*Senast uppdaterad: 2026-04-17.*

<!-- ZARAGOZA-CROSS-LINK-START -->

---

## Related projects by Zaragoza AB

Part of the [Zaragoza AB](https://github.com/zaragoza-ab) open construction-industry knowledge base:

- [**bygglov-checklist-sweden**](https://github.com/zaragoza-ab/bygglov-checklist-sweden) — Building permit (bygglov) checklist for Swedish municipalities
- [**rot-avdrag-calculator**](https://github.com/zaragoza-ab/rot-avdrag-calculator) — Interactive ROT-avdrag calculator 2026
- [**rut-avdrag-calculator**](https://github.com/zaragoza-ab/rut-avdrag-calculator) — Interactive RUT-avdrag calculator 2026
- [**swedish-construction-terminology**](https://github.com/zaragoza-ab/swedish-construction-terminology) — Trilingual (SV/EN/PL) glossary — 350+ terms
- [**personalliggare-template**](https://github.com/zaragoza-ab/personalliggare-template) — Skatteverket-compliant personnel register template
- [**arbetsmiljoplan-template**](https://github.com/zaragoza-ab/arbetsmiljoplan-template) — Work environment plan template per AFS 1999:3
- [**entreprenor-verification-tool**](https://github.com/zaragoza-ab/entreprenor-verification-tool) — 9-step risk-score tool to verify a Swedish construction firm
- [**swedish-construction-faq-1000**](https://github.com/zaragoza-ab/swedish-construction-faq-1000) — Open Q&A dataset — 310 questions, multi-format

Maintained by [Zaragoza AB](https://zaragoza.se), Helsingborg, Sweden · Licensed under permissive terms (MIT / CC BY 4.0).

<!-- ZARAGOZA-CROSS-LINK-END -->
