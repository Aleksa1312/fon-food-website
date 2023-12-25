# Dokumentacija rada "Food Website".

Na ovom projektu su radili:
- Aleksa Simovic 0388/2023
- Ognjen Urukalo 0361/2023
- Lazar Scepanovic 0992/2023

# O projektu:
"Food Website" je sajt za porucivanje hrane preko interneta. On se sastoji od 4 stranice, a one su sledece: 
- Home
- About
- Order
- Products

Tokom celog projekta se koristi font "Roboto" koji se dodaje sa sledecim kodom:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/73a58b62-d676-4f94-aa23-2a1bff89561d)

Uz ovaj font se sirom projekta koristi konstantna "color schema" do koje se dolazi putem css variable-a.

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/b5500758-f811-46ce-856b-0611615e76a5)

Prednosti koriscenja variable-a:
- Konsistan dizajn zbog pridefinisanog obima boja.
- Manje razmisljanje o zapisu boja ('var(--primary)' je lakse razumeti nego 'hex(#25f12e)')
- Lakse izmene u dizajnu (promena variable-a promeni svaki element gde je taj variable upotrebljen)

# O stranicama
U ovom delu je bolje objasnjena struktura stranica.

## Header
Header je komponenta koja se nalazi na vrhu svake stranice i sluzi za navigaciju izmedju Home i Order stranice.

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/599daf01-f3f9-4c83-8a32-1f78bca8b7ef)

Njegov izgled je postignut sa sledecim css-om:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/c28eca9c-9b58-48b3-99d9-ff59b31c7d70)
![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/8b16d262-603e-4f9a-9a79-8be274848315)

`.header {}` se bavi pozicioniranjem header-a na samoj stranici, a `.header-flow {}` se bavi izgledom elemenata u samom header-u.

## Footer
Footer je element koji se nalazi na dnu svake stranice i sluzi za navigaciju izmedju svih stranica koje postoje na sajtu.

## Home Stranica
Sastoji se iz 4 sekcije:
- Header
- Hero
- Call to action
- Footer

### Hero sekcija
Hero sekcija sluzi da privuce paznju kupcima i daje brz nacin da novi kupci vide sve prozivode sa "See Products" dugmetom koje vodi do Products stranice.

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/e2af7f3a-4e58-4c7e-8697-e7db8f7461a6)

Izgled ovog elementa je postignut sa absolutno pozicioniranom slikom koja sluzi zapravo kao "background". A tekst i dugme su vertikalno centrirani putem sledeceg koda:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/484980a0-92a4-4d01-ab13-bdfd752409da)

### Call to action sekcija
Call to action slicno kao hero poziva kupce da kupe nesto preko naseg sajta i daje lagan nacin da kupci posete Products stranicu:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/f4832252-011f-4c2c-a166-6b3f50edc911)

Ovaj izgled je postignut sa sledecim kodom:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/2e16fff4-4107-4d48-98e6-9f31326131ed)

U ovom kodu centriramo tekst sa `text-align: center;`, a elemente sa `display: flex;`, `flex-direction: column;`, `justify-items: center;` i `align-items: center;`

## About Stranica
Sastoji se iz 3 sekcije:
- Header
- About
- Footer

### About sekcija
Layout About stranice u html-u izgleda ovako:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/69de2c6d-0617-465f-b862-0ce40681ba39)

Ovde mozemo da vidimo da je cela stranica izradjena od `.about-paragraph` elemenata koji se sastoje iz `h1` + `p` tagova i kupcu bolje objasnjavaju o tome cime se bavi nas sajt.

Ovime se postize sledeci izgled stranice:

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/899301e7-6e4f-4842-ae31-3be8e9853d0d)

## Products Stranica
Sastoji se iz 3 sekcije:
- Header
- Products
- Footer

### Products sekcija

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/71824f55-2ddd-4323-aeb3-907e40b6c9ce)

Kao sto vidimo sa slike ona je napravljenja putem css grida koji ima 4 kolone i u svakoj se nalazi kartica koja sadrzi sliku, naziv, cenu i dugeme "poruci proizvod".

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/babcf1b5-3f6d-4a00-bf09-77803c579462)

## Order Stranica
Sastoji se iz 3 sekcije:
- Header
- Order
- Footer

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/9ace1bdb-1b2c-4f5b-88d7-ca1efa3dab21)

Na ovoj stranici mozemo pronaci layout sa 2 kolone koji je postignut putem `display: flex;`.

Sa leve strane se nalazi forma koja prikuplja informacije potrebne za dostavu. Forma se sastoji iz 3 input polja u koja korisnik upisuje svoje ime i prezime, adresu i sta zeli da poruci sa naseg sajta.

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/7b67d2e0-b0c8-4b87-bfec-2130f8232171)

Forma trentutno nije funkcionalna zato sto na sajtu nije koriscen JavaScript da posalje korisnikov input nasem serveru, pa klikom na "order" dugme korisnik biva preusmeren na laznu stranicu: "Order Success".

![image](https://github.com/Aleksa1312/fon-food-website/assets/102186502/6ae3a582-fb34-4ab7-bf6c-7fd34a2a6239)

# Kraj
Ovim se zavrsava ova prezentacija i nadam se da vam se svideo nas projekat. 😊
