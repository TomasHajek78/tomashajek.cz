# Maker Quest – Poznamky k projektu

Tento dokument obsahuje shrnutí konceptu a analýzy PDF podkladů pro nový projekt interaktivní webové aplikace pro Maker Faire.

## Koncept projektu
- **Cíl:** Motivovat děti a rodiny k delšímu a interaktivnějšímu pobytu na Maker Faire, rozvíjet jejich podnikavost a sbírat anonymizovaná data o jejich dovednostech.
- **Formát:** PWA (Progressive Web App) – přístup přes QR kód, bez nutnosti instalace z App Store.
- **Propojení:** Maker Faire + Prototýpci (www.prototypci.cz).

## Analýza podkladů (z PDF "MakerFaire praclist 2025")
Aplikace bude obsahovat 9 hlavních misí:
1. **Zahřívačka:** Checklist aktivit a prvních dojmů.
2. **Pozoruj & hodnoť:** Hledání unikátů a focení originální reklamy.
3. **Foto výzva:** Album 7 specifických snímků (vynález, nejlepší stánek, bláznivá věc atd.).
4. **Ptej se & inspiruj se:** Audio rozhovor s vystavovatelem (5 otázek).
5. **Produkty & výrobci:** Pochopení ceny, hodnoty práce a hledání extrémů (nejlevnější/nejdražší).
6. **Udržitelnost:** Průzkum ekologických aspektů makerství.
7. **Zkoušej & tvoř:** Lean Canvas pro děti (Problém, Zákazník, Řešení, Hodnota).
8. **Zhodnoť stánky:** Bodování 5 vybraných stánků.
9. **Celkové hodnocení:** Závěrečná reflexe a vygenerování certifikátu.

## Plánované funkce
- Integrovaný skener QR kódů.
- Nahrávání audia (pro rozhovory a reflexi).
- Fotografování přímo v aplikaci.
- Gamifikace: Sbírání odznaků (badges) za každou misi.
- Export anonymních dat o podnikavosti pro analýzu.
- (Později) Video-průvodce jednotlivými misemi.

## Technický stack (návrh)
- Next.js (Frontend & Backend), Tailwind CSS, Supabase (DB).

*Poznámka: Projekt bude realizován v nové složce "Maker Quest", jakmile bude zpřístupněna ve workspace.*
