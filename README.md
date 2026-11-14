# Reta Srbija — kod za Claude Code

Ovo je kompletan izvorni kod glavnog sajta https://retasrbija.rs, preuzet iz objavljene verzije 5, 13. novembra 2026. Uključeni su početna stranica, slike i objavljeni blog post.

## Pokretanje

1. Raspakuj ZIP.
2. Otvori ceo folder `retasrbija-claude-code` u VS Code-u i pokreni zvaničnu ekstenziju Claude Code. Ako koristiš Claude Code iz terminala, pokreni ga iz ovog foldera.
3. Claude će imati projektna uputstva u fajlu `CLAUDE.md`. Možeš mu napisati: „Pročitaj CLAUDE.md, pregledaj sajt i izmeni [opis izmene].”
4. Za lokalni pregled, ako je Python 3 instaliran, pokreni u terminalu iz ovog foldera:

```bash
python3 -m http.server 8000 --bind 127.0.0.1 --directory dist
```

Zatim otvori http://localhost:8000. Server zaustavljaš prečicom Ctrl+C.

Sajt koristi običan HTML i CSS. Nema instaliranja npm paketa niti build komande. Fajlovi u `dist/` predstavljaju izvor za uređivanje i sadržaj koji se objavljuje.

## Gde se šta nalazi

| Fajl | Sadržaj |
| --- | --- |
| `dist/index.html` | Početna stranica |
| `dist/styles.css` | Zajednički stilovi |
| `dist/assets/` | Slike |
| `dist/blog/retatrutid-triumph-1-rezultati-faze-3/index.html` | Objavljeni blog post |
| `dist/sitemap.xml` | Mapa sajta |
| `dist/robots.txt` | Uputstvo za pretraživače |
| `.openai/hosting.json` | Konfiguracija postojećeg Sites projekta |

## Uređivanje i objavljivanje

Izmene u ovom folderu menjaju lokalnu kopiju. Ne objavljuju se automatski na retasrbija.rs. U paketu nema lozinki, pristupnih tokena niti trajnog pristupa postojećem Sites hostingu.

Za objavu kroz postojeći Sites projekat možeš vratiti izmenjene fajlove u ovaj ChatGPT projekat. Za zajednički rad oba asistenta može se povezati privatni GitHub repozitorijum; vezu repozitorijuma sa objavljivanjem potrebno je podesiti zasebno. Postojeći domen i DNS nisu promenjeni.

`shop.retasrbija.rs` i `bakteriostatskavoda.rs` su zasebni projekti i nisu sadržani u ovom paketu.

Zvanična uputstva za Claude Code u VS Code-u: https://code.claude.com/docs/en/vs-code

Detalji izvorne verzije i kontrolne sume su u `SOURCE.json`.
