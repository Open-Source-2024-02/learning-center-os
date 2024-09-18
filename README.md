# ACME Learning Center Web Application

## Summary

ACME Learning Center Application, illustrating CRUD behavior and in-app navigation, with Angular Router. It also uses a JSON Server fake API.

## Features

Features includes are:

- Material Design
- Internationalization (i18n)
- Environment configuration
- JSON Server Fake API
- CRUD ops
- In-App Navigation
- Domain-Driven-Design approach

## Frameworks and Libraries

- Angular Material
- ngx-translate
- ngx-translate/http-loader
- JSON Server stable version 0.17.4

## Fake API start

```
cd server
sh start.sh
```

## Development  Server

Run ``ng serve`` for a dev server. Navigate to `http://localhost:4200/`.
```
ng serve
json-server --watch public/server/db.json
```

## Build

Run `ng e2e` for build app.
```
ng e2e
```
