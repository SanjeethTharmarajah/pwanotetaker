# Just Another Text Editor (J.A.T.E)

## Description

J.A.T.E is a Progressive Web Application (PWA) that runs in the browser, offline and can be installed locally to your machine. This application features a number of data persistence techniques, insuring the application runs regardless of browser supported function. J.A.T.E uses an IndexedDB database and the idb package. This application is deployed to Heroku, to access it in production continue reading the documentation!

### User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria 

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Acheivements

Added all configurations and code to make the app running according to acceptance criteria...

## Installation

TO run the app locally

1. Clone this repo

2. Run npm i to install all dependencies

3. To run the application: npm run start

</br>
The following animation demonstrates the application's functionality:


![J A T E Demo](https://user-images.githubusercontent.com/107900180/206565673-960dc4c8-1d0e-447e-9606-88ef539e1031.gif)

</br>

The following image shows the application's ```manifest.json``` file:
![manifest](https://user-images.githubusercontent.com/107900180/206566689-e37bb4b2-783b-4328-afe6-16664b20181b.png)

</br>
The following image shows the application's registered service worker:

![serviceworker](https://user-images.githubusercontent.com/107900180/206567108-41efd859-b8d6-480b-8dc2-d383c4a76d06.png)

</br>
The following image shows the application's IndexedDB storage:

![idb](https://user-images.githubusercontent.com/107900180/206567448-c4d0939a-4690-4b40-a597-476b1e1c0c19.png)


