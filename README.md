# Anamnestický dotazník
Vývoj anamnestického dotazníku pro web [diagnostikaditete.cz](https://diagnostikaditete.cz). Volně dostupné pro použití v praxi.

**Náhled aktuální verze:** https://strojiladam.github.io/anamnesticky-dotaznik/

---

## Patch Notes

### 2.1-alpha
#### Ukládání a práce s daty
- Přidáno manuální průběžné uložení.
- Přidáno automatické průběžné ukládání.
- Přidáno manuální znovunačtení posledního průběžného uložení.
- Přidána možnost vymazání historie a aktuálního průchodu.
- **Nový export a import JSON souboru**:
  - Umožňuje přenést průchod mezi zařízeními.
  - Klient může přinést vyplněný dotazník v souboru JSON specialistovi.
  - Alternativa při problémech exportu do PDF (např. na telefonu) — specialista si PDF vytvoří na svém zařízení.
  - Někteří specialisté mohou upřednostnit ukládání a načítání editovatelných souborů ve formátu JSON přímo ve svém zařízení, namísto archivace výsledků ve fixním PDF nebo v tištěné podobě.

#### Uživatelské rozhraní
- Nový úvodní a závěrečný blok s přehledem funkcí (ukládání, export, instrukce).
- Přidány nové sekce **Škola** a **Školka**.
- Drobné úpravy rozložení pro mobilní zařízení.

---

### 2.0-alpha
- **Nová funkce náhledu tisku**:
  - Zobrazuje orientační vzhled budoucí tištěné nebo PDF verze.
  - Pomáhá řešit problémy exportu do PDF na mobilních zařízeních.
  - Lépe pracuje s automaticky rozbalovacími seznamy a jejich chováním při tisku.

---

### 1.1.2-alpha
- Upraven design volby „Bez odpovědi“ (červené zvýraznění, přesun na konec nabídky).
- Přidána dynamická indikace nezodpovězených otázek (modrý puntík).
- Tištěná verze nově označuje nezodpovězené položky červenou hvězdičkou.

---

### 1.1.1-alpha
- Podmíněné zobrazování nově využívá plynulou animaci.
- Sjednocen vzhled a chování napříč prohlížeči (písmo, styl aktivních polí, odstranění nativních prvků jako šipky a scrollbary).

---

### 1.1-alpha
- Nahrazení rozbalovacích seznamů přehlednějšími multiple-choice položkami včetně volby „Bez odpovědi“ („–“).
- Odpovědi jsou nyní umístěny pod otázkami pro lepší čitelnost.
- Upravená struktura zamezuje rozdělování otázek a odpovědí při exportu do PDF.
- Přidán nový informační blok *„Proč se ptáme?“*.
- Doplněna a sjednocena logika podmíněného zobrazování.
- Pole „Věk“ automaticky skloňuje jednotky (rok/roky/let; měsíc/měsíce/měsíců).
- Přidána možnost lokálního uložení, načtení a smazání průchodu (zatím testovací režim).
- Další drobná vylepšení.

---

### 1.0-alpha
- Vytvoření dotazníku s jednoduchým dynamickým zobrazováním otázek
- Základní možnost tisku

---

*Technické zpracování a design:*

© Adam Strojil, 2025.  
All rights reserved.
