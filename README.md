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

## Published application

The application is published with EAS Update on the `main` branch. Scanning the
QR code below opens the update, which can be previewed with Expo Go or a
development build:

![QR code of the published update](./docs/expo-update-qr.png)

[Open the update](https://expo.dev/preview/update?message=Rate%20repository%20app&updateRuntimeVersion=1.0.0&createdAt=2026-08-28&slug=exp&projectId=120eb884-9c80-444c-a548-4c3c00765f11&group=5b09f6fc-6aff-43bd-84ff-78cf1e38ccde)

Publishing a new update:

```bash
cd rate-repository-app
eas update --branch main --message "..."
```

## Linting and tests

```bash
npm run lint
npm test
```
