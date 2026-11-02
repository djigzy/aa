# UPUTE ZA UPRAVLJANJE PROJEKTIMA (PROJECTS)

Ovaj direktorij automatski stvara i ažurira kartice projekata na cijeloj web stranici:

## 1. Dodavanje novog projekta
- Dovoljno je u ovom direktoriju (`src/assets/projects/`) stvoriti novu mapu, npr.:
  `09-novi-projekt/` ili `most-peljesac/`
- Dodavanjem nove mape na web stranici se automatski pojavljuje nova kartica projekta!

## 2. Dodavanje slika za projekt
- U mapu projekta postavite fotografije (npr. `.jpg`, `.jpeg`, `.png`, `.webp`).
- Možete postaviti onoliko slika koliko želite (1, 5, 10, 20...).
- Prva slika (abecedno/numerički npr. `01_slika.jpg`) koristi se kao glavna slika na naslovnoj kartici projekta.
- Sve postavljene fotografije automatski se prikazuju na podstranici projekta u galeriji.

## 3. Naziv i podaci o projektu (opcionalno info.json)
U mapu projekta možete postaviti datoteku `info.json` s detaljima, primjer:
```json
{
  "title": "Brodogradilišta",
  "subtitle": "Viktor Lenac",
  "year": "2024"
}
```
*Ako ne stavite `info.json`, sustav će automatski generirati naziv projekta iz samog naziva mape (npr. `09-tunel-ucka` -> `Tunel Ucka`).*
