# Full Stack Open: React Native

Rate Repository -sovellus, joka on toteutettu Expolla ja React Nativella.

## Rakenne

```
rate-repository-app/   Expo-sovellus
```

## Käyttö

```bash
cd rate-repository-app
npm install
npm start
```

Sovelluksen käyttämä GraphQL-osoite luetaan ympäristömuuttujasta `APOLLO_URI`
(katso `.env.example`). Backend on erillinen `rate-repository-api`, joka
käynnistetään omassa hakemistossaan.

Lintterin ja testit saa ajettua komennoilla:

```bash
npm run lint
npm test
```
