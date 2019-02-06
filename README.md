# DL-BUILD-KIT-2019

## NPM & Webpack based Front-End Build Kit (Incl. Babel/ES6 & Sass/SCSS)

### Goals
This project is intended scratch a personal itch. There are a lot of really good frameworks out there with some really nice out-of-the-box build tools. But occasionally I need to put something together for the purposes of testing or prototyping that is framework agnostic, minimalist, and maintains a separation of concerns between HTML, CSS, and JavaScript. This Build Kit incorporates node-sass for CSS/SCSS compilation and Babel for JavaScript-ES6 compatibility, but otherwise I've tried to keep everything "vanilla."  

### Setup
This project was built using Node.js (v10.15.0) and NPM (v6.4.1)
```
npm install
```

### Live Development
```
npm start
```

### Development Build
```
npm run dev
```

### Production Build
```
npm run build
```

### Font

I included the [Titillium Web](https://fonts.google.com/specimen/Titillium+Web) font in the build. Mostly for the sake of having a font as part of the build process, and partially because I kinda like it --DL