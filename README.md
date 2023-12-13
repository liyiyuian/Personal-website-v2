# Installation

I am not familiar with javascript, so there must be a better way... I first try to install nodejs with nvm, v18.19.0, but got errors.

Then I tried to install with conda, v20.9.0, then `npm i node-gyp --force`, then `npm audit fix --force`. Even though it is still showing some warnings, it works.

1. Install the Gatsby CLI
```
npm install -g gatsby-cli
```
2. Install dependencies
```
yarn
```
3. Start the development server
```
npm start
```
4. Generate a full static production build
```
npm run build
```
5. Preview the site as it will appear once deployed
```
npm run serve
```

To push: 
Install with:
```
npm install -g gh-pages --save-dev
```

Deploy with:
```
gh-pages -d public -b main
```