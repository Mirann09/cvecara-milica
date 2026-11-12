# Cvećara Milica, demo sajta

Demo početne strane za Cvećaru Milica kod groblja Orlovača, Beograd.
Čist HTML, CSS i JavaScript, bez biblioteka. Radi na GitHub Pages bez podešavanja.

## Šta je u folderu

- `index.html` ceo sajt: početna, ponuda, kontakt i četiri članka sa savetima
- `images/` fotografije radnje i venaca

## Objava na GitHub Pages

1. Napravi novi repozitorijum, na primer `cvecara-milica-demo`. Mora da bude Public.
2. Klikni Add file, pa Upload files.
3. Prevuci `index.html`, `README.md` i ceo folder `images`. Fajlovi moraju da budu u korenu repozitorijuma, ne u podfolderu.
4. Klikni Commit changes.
5. Idi na Settings, pa Pages. Pod Source izaberi Deploy from a branch, branch `main`, folder `/ (root)` i klikni Save.
6. Posle minut ili dva sajt je na adresi `https://TVOJE-KORISNICKO-IME.github.io/cvecara-milica-demo/`

## Pre nego što sajt postane pravi

- Obriši red `<meta name="robots" content="noindex, nofollow">` u `index.html`. Dok taj red stoji, Google ne prikazuje stranu u pretrazi.
- Popuni sve sa spiska "PROVERITI SA MILICOM" na vrhu `index.html`.
- Forma za upit još ne šalje poruke. Treba je povezati sa servisom za forme ili sa mejlom.
