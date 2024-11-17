# Installation

I am not familiar with Javascript, so there must be a better way handling this situation. I tried to install nodejs with nvm, v18.19.0, but got errors. Then I tried to install with conda, v20.9.0, then `npm i node-gyp --force`, then `npm audit fix --force`. Even though it is still showing some warnings, it works.

As for installation, I did:
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

For deploying the website, I did:
1. Generate a full static production build
```
npm run build
```
2. Preview the site as it will appear once deployed
```
npm run serve
```

To push to GitHub with `gh-pages`:

Install with:
```
npm install -g gh-pages --save-dev
```


To push to username.github.io with `gh-pages`:
```
git remote add gh-pages git@github.com:username/username.github.io.git
```

Verify with:
```
git remote -v
```

Deploy with:
```
gh-pages -d public -r git@github.com:username/username.github.io.git -b main
```


# Credit
Thanks to [Brittany Chiang](https://brittanychiang.com/) for the inspiration for this website. Her fourth version was a great starting point. Awesome work!
