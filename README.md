## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example

To reproduce in Safari:

```bash
npm install
npm run start // will start vite. 
Open browser at http://localhost:3000
```

Changes in src/index.html will be automatically reflected in browser.

To reproduce on iPhone, with XCode on your Mac, and your iPhone tethered:

```bash
npm install
npm run build
npx cap sync
npx cap open ios

```
In XCode, run on your Iphone. Drag the slider up or down, and you will see it moves erratically.

The rendered html is at src/index.html

After changes in src/index.html, redeploy with:

```bash
npm run build
npx cap sync
npx cap open ios

```
Stop and restart the app.



