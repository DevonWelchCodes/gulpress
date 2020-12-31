Smarttpress
===

Hi. I'm a starter theme called `smarttpress`, built specifically for the Smartt agency from Vancouver, BC, Canada.

I come packed with modern build tools such as; Gulp, Webpack, Sass, Production mode, Browsersync and Tailwind.

Getting Started
---------------

Git clone the theme, then checkout which branch you want to use for your project!

Use `master` branch for the basic configuration (No Woocommerce).
Use git checkout `smarttpress-woo` to use the Woocommerce configuration.

⚠️ WARNING: Before doing anything else on the theme, `delete` the .git file. ⚠️

Getting the theme set up on local
---------------
Run in the theme root `yarn` to do a first time setup. (this grabs node_modules, package.lock and other files required to run the theme).

You will also want to setup your local website URL. Change the URL in `gulpfile.babel.js` Search for _**// put your local website link here**_

Build commands
---------------

###### Watch Mode
`yarn watch` To put your theme in "watch" mode (Watches for SCSS and JS Changes, then reloads the browser) type in the theme root `yarn watch`

###### Build Mode
`yarn build` To put your theme into build mode (ready for production) type in theme root `yarn build`

Then your ready to get hacking!

Good luck!
