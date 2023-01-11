# PWA Text Editor

## Description

The application shows a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.


## Functionality

Given a text editor web application, when a user opens their application the editor the see a client server folder structure and a backend server.

When the user runs `npm run start` from the root directory, the application starts up the backend and serves the client.

When the user runs the text editor application from the terminal, they see that the JavaScript files have been bundled using webpack.  

When running weback plugins, the user will have a generated HTML file, service worker and a manifest file.

When the user uses next-gen JavaScript in the application, they find that the text editor functions in the browser.

When the user opens the text editor, they find that the IndexedDB has created a database storage.

When the user enters content and then clicks off the DOM window, they find that content in the text editor has been saved with IndexedDB.

When the user reopens the text editor after closing it, they find that the content in the text editor has been retrieved from IndexedDB.

When the user clicks on the Install button, then a web application with an icon is downloaded on their desktop.

When the user loads the web application, they will have a registered service worker using workbox.

When the user registers a service worker, they will have static assests pre cached upon loading, along with subsequent pages and static assets.

When deployed to Heroku the user will have build scripts for a webpack application.

## Code

The application uses IndexedDB to create an object store and includes both GET and PUT methods

The application works without an internet connection

The application automatically saves content inside the text editor when the DOM window is unfocused

The code is bundled with webpack

A service worker with workbox Caches static assets

The application uses babel in order to use async / await

The application uses has a generated `manifest.json` using the `WebpackPwaManifest` plug-in.

The application can be installed as a Progressive Web Application.


## Installation

The code for this project can be found on GitHub at: https://github.com/c-alanwill/PWA-Text-Editor

The application is deployed to Heroku at: https://pwa-text-editor-cw.herokuapp.com/


## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished app being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished app with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished app with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished app with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

## Credits

N/A

## License

Please refer to the license in the repo.

## Contributing

N/A