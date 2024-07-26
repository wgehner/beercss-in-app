## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example



To reproduce, with XCode on your Mac, and your iPhone tethered:

```bash
npm install
// npm run start //should open a browser, but we want to run in ios app:
npm run build
npx cap sync
npx cap open ios

```
In XCode, run on your Iphone. Bleeding into safe area. Rotate. Same.

This is what WebKit WebView does, but behavior can be changed with --safe-area-inset-[top...]

The rendered html is at src/index.html

Uncomment the meta viewport and style in src/index.html. To redeploy:

```bash
npm run build
npx cap sync
npx cap open ios

```
Stop and restart the app.

Portrait now seems ok at first sight, but landscape is visibly broken.

It appears that the nav and main.responsive margins are not relative to the body.

