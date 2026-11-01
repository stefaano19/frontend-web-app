# Frontend

An Angular web application for managing a car dealership. The Italian-language interface includes customer registration and login, a dashboard for cars and products that need reordering, and management screens for suppliers, manufacturers, vehicles, products, appointments, and purchase orders.

## Tech stack

- Angular 11.2 and TypeScript
- Angular Material and SCSS
- RxJS for API requests
- Jasmine and Karma for unit tests

## Requirements

- Node.js and npm compatible with Angular CLI 11
- The dealership API running at `http://localhost:8080` for features that load or save data

The development API URL is configured in `src/environments/environment.ts`. This repository contains the frontend; it does not include the API server.

## Setup and run

```sh
npm ci
npm start
```

Open [http://localhost:4200](http://localhost:4200). The Angular development server reloads the app when source files change.

## Build and tests

```sh
npm run build
npm test -- --watch=false
```

The build output is written to `dist/Frontend`. Unit tests run with Karma and require a compatible browser.
