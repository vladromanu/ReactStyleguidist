# React Styleguidist
Sample of a React Styleguidist implementation is key to a good design system

There are 2 options to start this: 
* Basic Stypeguidist example with just the components
* Create React App Styleguidist example to incorporate all into a React app

Choose either of the above and stick to it !

Add these commands into your package.json’s scripts section:
```
{
  "scripts": {
    "styleguide": "styleguidist server",
    "styleguide:build": "styleguidist build"
  }
}
```

Start by:
```
npm install 

npx styleguidist server
npx styleguidist build
```

Many thanks to [React Styleguidist](https://react-styleguidist.js.org/)
