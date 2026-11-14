# Reta Srbija

## Projekat

Glavni javni sajt: https://retasrbija.rs

Ovo je statički HTML/CSS sajt na srpskom jeziku, latinicom. Folder `dist/` je i izvor za uređivanje i direktorijum koji hosting objavljuje. Nema framework-a, npm zavisnosti, build koraka, backend-a ili baze podataka.

- Početna stranica: `dist/index.html`
- Zajednički stilovi: `dist/styles.css`
- Slike: `dist/assets/`
- Blog: `dist/blog/retatrutid-triumph-1-rezultati-faze-3/index.html`
- SEO: `dist/sitemap.xml`, `dist/robots.txt`, meta podaci i JSON-LD u HTML-u
- Trenutni hosting: Sites, konfiguracija `.openai/hosting.json`

## Izgled i sadržaj

Prati postojeći izgled: svetla podloga, tamnoplavi tekst, plavi i crveni akcenti, tipografija Arial/Helvetica. Paleta: `#FBFCFE`, `#071D3B`, `#1455D9`, `#E53942`.

Zaglavlje sadrži RETA SRBIJA znak, info@retasrbija.rs, Shop i WhatsApp. Kontakt broj je +381 63 14 17 995; WhatsApp URL koristi `381631417995`.

Sajt sadrži edukativni sadržaj o retatrutidu, tirzepatidu, GHK-Cu, NAD+, BPC-157 i TB-500. Čuvaj postojeće izvore i jasno odvajanje istraživačkih rezultata od odobrenih primena. Ne izmišljaj medicinske tvrdnje, rezultate studija ili sertifikate.

`shop.retasrbija.rs` i `bakteriostatskavoda.rs` su zasebni projekti; njihov izvor nije u ovom folderu.

## Rad

- Uređuj HTML i CSS direktno, u obimu zadatka koji korisnik traži.
- Zadrži postojeće URL-ove i kanonski domen, osim kada korisnik zatraži promenu.
- Kod novih blog postova dodaj odgovarajući link na početnu stranicu, canonical i stavku u sitemap-u.
- Proveri da navigacija, slike i izgled na mobilnom i desktop prikazu rade posle izmene.
- Sažeto navedi promenjene fajlove i šta je provereno.

Lokalni pregled (ako je Python 3 dostupan):

```bash
python3 -m http.server 8000 --bind 127.0.0.1 --directory dist
```

Otvori http://localhost:8000. Nije potreban build.

## Objavljivanje

Ovaj izvoz ne sadrži pristupne podatke niti podešeno automatsko objavljivanje. `.openai/hosting.json` opisuje postojeći Sites projekat; sam fajl ne daje pristup hostingu. Nemoj označavati lokalne izmene kao objavljene bez potvrđenog rezultata objavljivanja.

Izmenjeni fajlovi mogu da se vrate u postojeći ChatGPT/Sites projekat radi objave. Deljeni privatni GitHub repozitorijum i način objavljivanja mogu da se povežu zasebno.
