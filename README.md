# Task Tracker

A browser-based task board built with React, Redux, and Material UI. Create and delete tasks, change their priority, and move them between queued, in-progress, and completed states. Includes local registration and login; users and tasks are stored in the browser's `localStorage`.

## Run

Requires Node.js and npm. No backend or environment variables are required by the current source.

```sh
npm ci
npm start
```

Open `http://localhost:3000`, register a local account, and sign in to use the board. Data stays in the browser where it was created.

## Build

```sh
npm run build
```

Creates production assets in `build/`, then runs Gulp to inline JavaScript and CSS into `build/index.html`. Other assets, such as images, may remain separate. Serve the `build/` directory with a static web server.
