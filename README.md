### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/onlook-dev/studio.git
   ```
2. Navigate to app folder
   ```sh
   cd app
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Run the project
   ```js
   npm run dev
   ```


## Usage

### Trying with demo project

We have a few demo projects included in the `demos` folder. These inside are a standard React app and a Next.js React app. 

These are already set up with the Onlook plugins and have code written to them directly.

To run, follow the following steps:

1. Run the demo project
   ```sh
   cd demos/next && npm install && npm run dev
   ```
2. Open Onlook studio
3. Point to `http://localhost:3000`

For more examples, please refer to the [Documentation](https://docs.onlook.dev)

### Using your own React project

To try with your own React + TailwindCSS project, follow the following steps:

1. Install the corresponding Onlook plugins for your React framework:
     1. [Nextjs](https://www.npmjs.com/package/@onlook/nextjs)
     2. [Babel (webpack, esbuild, vite, etc.)](https://www.npmjs.com/package/@onlook/babel-plugin-react)
2. Run your project in dev mode
3. Open Onlook studio to where your project is running locally. For example `http://localhost:3000`

The code for the plugins are under `plugins`.
