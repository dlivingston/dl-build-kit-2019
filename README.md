# DL-BUILD-KIT-2019

## NPM & Webpack based Front-End Build Kit (Incl. Babel/ES6 & Sass/SCSS)

### Goals
This project is intended scratch a personal itch. There are a lot of really good frameworks out there with some really nice out-of-the-box build tools. But occasionally I need to put something together for the purposes of testing or prototyping that is framework agnostic, minimalist, and maintains a separation of concerns between HTML, CSS, and JavaScript. This Build Kit incorporates node-sass for CSS/SCSS compilation and Babel for JavaScript-ES6 compatibility, but otherwise I've tried to keep everything "vanilla."  

This was also something of an exercise in leveling up my skills with Webpack, and an experiment in testing the capabilities of Webpack as a Front-End development kit. No doubt I’ve made mistakes or choices that aren’t optimal for large-scale web or application development. This is intended to be a tool kit for Front-End Devs (like myself) who don’t need a full-blown “framework” for one-off development or testing.  

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