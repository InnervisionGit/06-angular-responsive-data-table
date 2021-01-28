# DataTable

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## API - JSON Server

Run it in a docker container

`docker run -d -p 3000:80 -v ${PWD}/server/db.json:/data/db.json clue/json-server`
