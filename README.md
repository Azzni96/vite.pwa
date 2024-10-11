# Vite PWA Project

<img src="https://vitejs.dev/logo.svg" alt="Vite Logo" width="150"/>


This repository contains a fully functional Progressive Web Application (PWA) built using Vite. The application is designed to provide a fast and seamless experience, including features such as:

- **Offline capabilities**: The app can be used even without an internet connection.
- **Efficient performance**: Built with Vite, it ensures fast loading times and smooth navigation.
- **Progressive enhancements**: Optimized for both desktop and mobile users.

if you want to do build to dist two html you should write to vite.config.ts 
________________________________________
  build: {
  
    rollupOptions: {
    
      input: {
      
        index: './index.html',
        
        main: 'main.html'
        
      }
    }
  }
  
_______________________________________
Feel free to explore the source code, and contributions are welcome!
