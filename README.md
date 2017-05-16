# Spotitude
***
##This angular app allows dynamic search of Spotify artists
This app uses a base index.html into which is injected html from components. A class MusicService in services hits the spotify api url. The searchComponent class calls the methods from the services as you key-up while typing the artist name into the search box. The object returned from Spotify is mapped to a json format. The artist and album components display the data returned from Spotify to the screen. The classes in the album and artist files create arrays of the data to allow it to be displayed. A routing file is used to handle the links to the home and about page. The search results are stored in a array variable for use when you search for album tracks. Clicking on a track to preview it takes you to a new tab which opens a Spotify page. 
The webpage is made reponsive by using Twitter Bootstrap CDN links. A Bootswatch theme CDN is used for the colours and fonts.


This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.26.

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to GitHub Pages

Run `ng github-pages:deploy` to deploy to GitHub Pages.

## Further help

To get more help on the `angular-cli` use `ng help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
#   S p o t i t u d e 
 
 