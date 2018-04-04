# prettier-config-guestline

This package includes the shareable Prettier configuration used by [Guestline Scripts](https://github.com/guestlinelabs/scripts).<br>
Please refer to its documentation:

## Usage with Guestline Scripts

The easiest way to use this configuration is with [Guestline Scripts](https://github.com/guestlinelabs/scripts), which includes it by default.

**You don’t need to install it separately.**

## Usage Outside of Guestline Scripts

If you want to use this Prettier configuration in a project not built with Guestline Scripts, you can install it with following steps.

First, install this package and Prettier.

```sh
npm install --save-dev prettier prettier-config-guestline
```

Then create a file named `.prettierrc.js` with following contents in the root folder of your project:

```js
module.exports = require('prettier-config-guestline');
```

That's it! You can override the settings from `prettier-config-guestline` by editing the `.prettierrc.js` file. Learn more about [configuring Prettier](https://prettier.io/docs/en/options.html) on the Prettier website.
