# JournalMall Pro

> Researchad affärsmöjlighet från Nexar Academy. Den fullständiga marknadsresearchen
> ligger i skillen **affärsplan** — kör `/affarsplan` för att läsa den.

## Vad vi bygger
GDPR-säkra journalmallar för privata vårdgivare – redo att använda direkt, utan krångel. JournalMall Pro är ett komplett mallpaket för journalanteckningar anpassat till patientdatalagen och de nya reglerna som träder i kraft 2026. Till skillnad från tunga SaaS-system kommer du igång på minuter – ladda ned, anpassa och börja dokumentera korrekt redan idag. Passar alla privata vårdspecialiteter: läkarmottagningar, psykoterapeuter, fysioterapeuter, logopeder och fler.

## Stack (ändra inte utan att fråga)
- Next.js + Tailwind (frontend)
- Supabase (databas + auth)
- Vercel (deploy)
- Claude API där appen behöver AI

## Kommandon
- `npm run dev` — kör lokalt
- `npm run build` — bygg + felkoll (kör efter varje ändring)
- `npm run lint` — lint

## Så jobbar vi (viktigt)
- Bygg i **små steg** — kör `npm run build` efter varje ändring och visa resultatet.
- **Fråga vid större vägval** (tech, datamodell, pris) i stället för att gissa.
- Lägg **aldrig** hemligheter/nycklar i koden — bara i `.env.local`.
- Håll det **enkelt** — en MVP som bevisar värdet, inte en färdig produkt.

## Projektminne (DU ansvarar för det — användaren ska aldrig behöva be)
- Efter varje avklarat steg: uppdatera `docs/FRAMSTEG.md` (byggt + nästa steg).
- Vid varje vägval: logga en rad i `docs/BESLUT.md` (datum + 1 mening om varför).
- Bocka av i `docs/UPPGIFTER.md` allt eftersom.
- **Vid sessionsstart: läs `docs/FRAMSTEG.md` FÖRST** och sammanfatta "var vi var".
- Använd din inbyggda auto-memory för build-kommandon och buggfixar.

## Kom igång
**Kör `/start` först** — den frågar om din nivå och guidar dig hela vägen: förklarar varje verktyg (Supabase, Vercel m.m.), hjälper dig installera, och bygger appen steg för steg. Är du redan van kan du i stället be mig läsa `/affarsplan` och föreslå en MVP-plan direkt.

<!-- nexar:opportunity slug=journalmall-pro -->
