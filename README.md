# Notes README

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* NodeJS

  The following version of Node and Npm are required:

  * Node 8.x
  * Npm 3.x

* MongoDB

  MongoDB 3.x is required

### Build

There are 2 build options:

* Build

  ```javascript
  npm run build
  ```

* Build with watch enabled

  ```javascript
  npm run build:watch
  ```

### Run ESlint

* Lint project using ESLint

  ```bash
  npm run lint
  ```

* Lint project using ESLint, and autofix

  ```bash
  npm run lint:fix
  ```

### Run API Server

Before running the React application, the API needs to be started.

The following command wil start server and host api at http://localhost:8000/api

```javascript
npm run serve:api
```

### Run React App

* Run Dev Server

  Start React usinf React dev server

  ```javascript
  npm run serve:dev
  ```
----