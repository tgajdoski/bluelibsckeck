# check the bluelibs and live data

## Generate your project

```bash
npm run blueprint:generate
```

## Setup your microservices

```bash
cd microservices/api
npm install
npm run start:dev
```

```bash
cd microservices/ui
npm install
npm run generate # Run it first time or when GRAPHQL API Changes.
npm run start:dev
```
