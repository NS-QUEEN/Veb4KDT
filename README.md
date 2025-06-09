# Maailma Riigid – React rakendus

See rakendus kuvab teavet maailma riikide kohta, kasutades REST Countries API-t.

## Funktsioonid
- Riikide otsing nime järgi
- Tulemuste pagineerimine
- Iga riigi detailne vaade (lipp, nimi, pealinn, rahvaarv, pindala, keeled, valuutad jne)
- Moodne kasutajaliides (Material-UI)

## Tehnoloogiad
- React + hooks
- React Router
- Material-UI

## Käivitamine

1. Loo uus kataloog ning ava see VS Code’is.

2. Algata Reacti projekt:
Ava uus Terminal VS Code'is ning käivita

npx create-react-app .

3. Paigalda vajalikud lisateegid:

npm install @mui/material @emotion/react @emotion/styled react-router-dom

4. Alles siis asenda projekti vaikimisi failid õigete versioonidega.

5. Käivita rakendus:

npm start

Kui küsitakse 
    ? We're unable to detect target browsers.
    Would you like to add the defaults to your package.json? » (Y/n)
vajuta Y ja jätka.

6. Ava brauseris:

http://localhost:3000

## Kaustastruktuur

- `/public` – Staatilised failid (nt `index.html`), mis jõuavad otse brauserisse ja mille kaudu React rakendus käivitatakse
- `/src/pages` – Lehed (CountriesList, CountryDetail)
- `/src/App.js` – Põhirakendus
