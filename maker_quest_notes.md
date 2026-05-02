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

## Témata pro diskuzi (Zítra)

### 1. Offline režim a dostupnost dat
- **Řešení:** PWA (Progressive Web App) se Service Workery. Umožní dětem plnit úkoly i tam, kde je špatný signál (v halách výstaviště).
- **Technologie:** `IndexedDB` v prohlížeči pro ukládání fotek a audia přímo v mobilu. Jakmile se telefon připojí k Wi-Fi/4G, data se automaticky "dosypou" na server.

### 2. Webová vs. Nativní aplikace (iOS/Android)
- **Web (PWA):** Nulové bariéry (sken QR -> hra). Nižší náklady. Ideální pro jednorázovou akci jako Maker Faire.
- **Nativní:** Nutnost stahovat z App Store (velká bariéra). Výhoda jen pokud by aplikace měla sloužit celoročně s push notifikacemi.

### 3. Monetizace a škálování
- **B2C:** Přímá platba u vstupu (QR kód s platební bránou).
- **B2B:** Prodej licence celému Maker Fairu jako "oficiální doprovodný program".
- **Whitelabel:** Možnost upravit aplikaci pro jakýkoliv jiný festival nebo vědecké centrum.

### 4. Sběr a vyhodnocení dat
- **Storage:** Supabase (zabezpečená SQL databáze) – ideální pro anonymizovaná data o podnikavosti.
- **Analýza:** Dashboard (např. Grafana nebo vlastní admin panel), který v reálném čase ukazuje metriky: "Kde jsou děti nejvíce kreativní?", "Jaká témata je nejvíc pálí?".

*Všechny tyto body zítra probereme detailně! Dobrou noc.*
