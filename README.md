# Cool Text Editor 2

## User Story

As a developer, my goal is to generate notes or code snippets that can be accessed with or without an internet connection. The purpose of this is to ensure that I can easily retrieve this information in the future.

## Project Objective

As I progress through the course, I have developed projects to showcase to potential employers, and the current text editor project stands out as it utilizes the latest concepts I've learned. My goal is to create a single-page text editor that runs on the browser, meets PWA criteria, and supports various data persistence techniques to ensure redundancy in case of browser limitations. To achieve this, I will start with an existing application and use the idb package to implement storing and retrieving data on an IndexedDB database.

## Acceptance Criteria

When you open the text editor web application in your editor, you should see a client-server folder structure. Running npm run start from the root directory will start the backend and serve the client. After running the webpack plugins, you will have a generated HTML file, service worker, and a manifest file. By using next-gen JavaScript in your application, the text editor should still function without errors, and IndexedDB will immediately create a database storage upon opening the text editor. After entering content and clicking off the DOM window, the content will be saved with IndexedDB. Upon reopening the text editor, the content will be retrieved from IndexedDB. Clicking on the Install button will download the application as an icon on your desktop, and registering a service worker using workbox will ensure that your static assets are pre-cached upon loading, along with subsequent pages and static assets. Deploying to Heroku will require proper build scripts for a webpack application.

## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)


### Technical Tools

In addition to meeting the above acceptance criteria, the application uses IndexedDB to create an object store and include both GET and PUT methods. The application should also function without an internet connection and automatically save content inside the text editor when the DOM window is unfocused. It is bundled with webpack and create a service worker with workbox to cache static assets. Babel should be used to implement async/await functionality. The application has a generated manifest.json using the WebpackPwaManifest plug-in and is installable as a Progressive Web Application.

Uses the Expressjs package (https://expressjs.com/)

Deploys to heroku(https://heroku.com)

Uses the IndexedDB API to store significant amounts of structured data, including files and blobs, IndexedDB is the low-level API you should use. It uses indexes for high-performance searches. Here is one source for documentation(https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

## License

![license](https://img.shields.io/badge/license-MIT-blue.svg)

## 📝 Notes

- These are the (2) items required for submission
  1.  The URL of the heroku deployment
       https://

      
  2.  The URL of the GitHub repository that contains your code
      https://github.com/phagn131/cool-text-editor-2

## Contact Information:
- Github: [phagn13@github.com](https://github.com/phagn13@github.com)
- Email: [chloetechnologies@gmail.com](user@email.com)
