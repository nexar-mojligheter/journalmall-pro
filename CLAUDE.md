# JournalMall Pro

> **STOPP — gör detta allra först:** kör skillen `/start`. Föreslå INGEN plan och ställ
> INGA tekniska frågor innan dess. `/start` leder användaren (som kan vara helt ny) steg
> för steg. **Du LEDER och fattar alla tekniska beslut själv** (logga i docs/BESLUT.md) —
> be aldrig användaren välja tech, integration eller betalning.
>
> Researchad möjlighet från Nexar Academy. Full marknadsresearch finns i skillen `/affarsplan`.

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
- **DU leder.** Användaren kan vara helt ny — håll dem i handen, ett steg i taget, förklara i vardagsspråk.
- **Ta tekniska beslut själv** (tech, datamodell, integrationer, betalning) med sunda standardval och logga dem i `docs/BESLUT.md`. Dumpa ALDRIG tekniska val på användaren.
- Fråga bara om sånt användaren faktiskt har en åsikt om — i vardagsspråk och med en tydlig rekommendation. Föreslå EN väg, inte en meny av alternativ.
- Bygg i **små steg** — kör `npm run build` efter varje ändring och visa resultatet.
- Lägg **aldrig** hemligheter/nycklar i koden — bara i `.env.local`.
- Håll det **enkelt** — en MVP som bevisar värdet.

## Projektminne (DU ansvarar för det — användaren ska aldrig behöva be)
- Efter varje avklarat steg: uppdatera `docs/FRAMSTEG.md` (byggt + nästa steg).
- Vid varje vägval: logga en rad i `docs/BESLUT.md` (datum + 1 mening om varför).
- Bocka av i `docs/UPPGIFTER.md` allt eftersom.
- **Vid sessionsstart: läs `docs/FRAMSTEG.md` FÖRST** och sammanfatta "var vi var".
- Använd din inbyggda auto-memory för build-kommandon och buggfixar.

## Kom igång
**Kör `/start` — alltid, först av allt.** Den leder dig (och mig) steg för steg från noll till färdig app: frågar om din nivå, förklarar varje verktyg (Supabase, Vercel m.m.), hjälper dig installera, och bygger. Föreslå INTE en MVP-plan på egen hand — kör `/start`.

<!-- nexar:opportunity slug=journalmall-pro -->
