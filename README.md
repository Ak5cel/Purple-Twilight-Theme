# Purple Twilight

![](https://img.shields.io/badge/AMO_listing_status-awaiting_review-yellow)

A mod of the [Purple Night Theme](https://addons.mozilla.org/en-US/firefox/addon/purple-night-theme/) for Firefox by [breuxi](https://addons.mozilla.org/en-US/firefox/user/16198217/) - for the same pretty colours, but without the twinkling stars for a more minimal look.

## Setup

### Requirements
Make sure you're using a current LTS (long term support) version of [Node.js](https://nodejs.org/en/). Then install `web-ext`, which you can do by either cloning this repository and running

```sh
npm install
```
or manually install for the project by running
```sh
npm install --save-dev web-ext
```
(more instructions at [web-ext](https://github.com/mozilla/web-ext))

### Build and Test
Build the extension by running 
```sh
npm run build
```

To test the extension in Firefox, run
```sh
npm run dev
```
If you're using a different version of Firefox on Desktop than the default, use the `--firefox` option like 
```sh
npm run dev -- --firefox=deved
```
Some other options for `--firefox` include `nightly` and `beta`. For more detailed instructions and use-cases, refer the web-ext docs [here](https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/#using-web-ext-section) and [here](https://extensionworkshop.com/documentation/develop/web-ext-command-reference/#web-ext-run).

## License
Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)

Feel free to mod this to make it your own, but do credit the authors and share under the same license🤝

💜

