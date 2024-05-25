# baldwins-net

Code for [Baldwins.net](https://baldwins.net), primarily used for random things, like Christmas rotation lists.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.

The app uses [Reagent](https://reagent-project.github.io), a minimalistic interface between ClojureScript and React.<br>
You can use existing npm React components directly via a [interop call](http://reagent-project.github.io/docs/master/InteropWithReact.html#creating-reagent-components-from-react-components).

Builds use [Shadow CLJS](https://github.com/thheller/shadow-cljs) for maximum compatibility with NPM libraries. You'll need a [Java SDK](https://adoptopenjdk.net/) (Version 8+, Hotspot) to use it. <br>
You can [import npm libraries](https://shadow-cljs.github.io/docs/UsersGuide.html#js-deps) using Shadow CLJS. See the [user manual](https://shadow-cljs.github.io/docs/UsersGuide.html) for more information.

### `npm run cards`

Runs the interactive live development enviroment.<br>
You can use it to design, test, and think about parts of your app in isolation.

This environment uses [Devcards](https://github.com/bhauman/devcards) and [React Testing Library](https://testing-library.com/docs/react-testing-library/intro).

### `npm run build`

Builds the app for production to the `public` folder.<br>
It correctly bundles all code and optimizes the build for the best performance.

Your app is ready to be deployed!

## Other useful scripts

### `null` and `npm run e2e`

You can use `null` to run tests a single time, and `npm run e2e` to run the end-to-end test app.
`npm test` launches tests in interactive watch mode.<br>

See the ClojureScript [testing page](https://clojurescript.org/tools/testing) for more information. E2E tests use [Taiko](https://github.com/getgauge/taiko) to interact with a headless browser.

### `npm run lint` and `npm run format`

`npm run lint` checks the code for known bad code patterns using [clj-kondo](https://github.com/borkdude/clj-kondo).

`npm run format` will format your code in a consistent manner using [zprint-clj](https://github.com/clj-commons/zprint-clj).

### `npm run report`

Make a report of what files contribute to your app size.<br>
Consider [code-splitting](https://code.thheller.com/blog/shadow-cljs/2019/03/03/code-splitting-clojurescript.html) or using smaller libraries to make your app load faster.

### `npm run server`

Starts a Shadow CLJS background server.<br>
This will speed up starting time for other commands that use Shadow CLJS.

## Useful resources

Clojurians Slack http://clojurians.net/.

CLJS FAQ (for JavaScript developers) https://clojurescript.org/guides/faq-js.

Official CLJS API https://cljs.github.io/api/.

Quick reference https://cljs.info/cheatsheet/.

Offline searchable docs https://devdocs.io/.

VSCode plugin https://github.com/BetterThanTomorrow/calva.