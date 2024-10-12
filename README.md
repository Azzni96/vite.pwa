<img src="https://vitejs.dev/logo.svg" alt="Vite Logo" width="150"/>
Vite PWA Project

Installation
Before getting started, install the PWA plugin by running the following command in your terminal:

``
bash
``
``
npm install -D vite-plugin-pwa
``

Once installed, you can copy and use the following code.

Project Features
This repository contains a fully functional Progressive Web Application (PWA) built using Vite. The application is designed to provide a fast and seamless experience with the following features:

Offline capabilities: The app can be used even without an internet connection.
Efficient performance: Built with Vite to ensure fast loading times and smooth navigation.
Progressive enhancements: Optimized for both desktop and mobile users.
Building with Two HTML Files
If you want to build the project with two separate HTML files (index.html and main.html), add the following configuration to your vite.config.ts file:

```ts 
// vite.config.ts
build: {
  rollupOptions: {
    input: {
      index: './index.html',
      main: 'main.html'
    }
  }
} 
```
Contributing
Feel free to explore the source code, and contributions are welcome!
