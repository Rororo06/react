# Full Stack Open: React Native

Rate Repository application built with Expo and React Native.

| Directory | Contents |
| --- | --- |
| [rate-repository-app](./rate-repository-app) | Expo application: repository list, single repository view, reviews, sign in and sign up |

Node 22 is expected.

## Running the application

```bash
cd rate-repository-app
npm install
cp .env.example .env       # EXPO_PUBLIC_APOLLO_URI
npm start
```

The GraphQL server address is read from the `EXPO_PUBLIC_APOLLO_URI`
environment variable. The backend is the separate `rate-repository-api`
project, which is started in its own directory and listens on
http://localhost:4000 by default.

## Linting and tests

```bash
npm run lint
npm test
```
