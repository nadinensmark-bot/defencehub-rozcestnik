# Defence Hub rozcestník 🚀

NFC landing page s odkazy Defence Hubu — web, DH Kompas (demo), LinkedIn,
databáze řešení a WhatsApp komunita. V brand barvách Defence Hubu,
s raketovou animací při otevření.

**Živá stránka:** https://nadinensmark-bot.github.io/defencehub-rozcestnik/

Nasazuje se automaticky přes GitHub Actions při každém pushi do `main`.

## Klíčenky a parametry (od 16. 9. 2026)

- Karty: Uložit kontakt (vCard) · Pošlete nám kontakt (mailto, chytá Power Automate do Excelu) · Domluvit konzultaci · Web · Akce · NATO DIANA · Databáze řešení · LinkedIn. DH Kompas (demo) a WhatsApp komunita jsou zakomentované.
- Osobní klíčenka: `?who=nadine` (`leos`, `katka`, `martin`, `honza`), volitelně `&go=vcard` (rovnou nabídne vizitku).
- Rozdávací klíčenka: bez parametrů (obecná vizitka DH, předmět mailu `Kontakt | klicenka | tym`).
- Konfigurace (sběrná schránka, tým, kdo je kdy kde) je v `index.html` v bloku `DH_CONFIG` nahoře ve skriptu. Nic jiného se needituje.
- Vizitky: `vcf/*.vcf` (vCard 3.0). Hodnoty `[DOPLNIT]` nahradit před nasazením.
- Předmět mailu je strojově čtený: `Kontakt|Contact | <akce> | <jméno>`; názvy akcí bez diakritiky a bez `|`.
- `wp-blok.html` je starší kopie pro WordPress a zatím NENÍ aktualizovaná.
