LiveBetterClient
================

The current build can be found at [https://st-team5.github.io/LiveBetterClient/](https://st-team5.github.io/LiveBetterClient/).

How to
======

Prepare your environment
------------------------
1. Install Node.js, if necessary.
1. Open a terminal.
1. Install yeoman globally: `npm install -g yo`
1. Install grunt globally: `npm install -g grunt grunt-cli`
1. `cd` to the directory of this project
1. Run `npm install` in the directory of this project to install all dependencies.

Run a local webserver for development
-------------------------------------
Run `grunt serve` in a terminal

Now open [http://localhost:9000/](http://localhost:9000/). Grunt will automatically watch for changes, so you just need to save your files and the server will reload.

Deploy to GitHub pages
----------------------
1. Verify that everything is OK. Commit and push all your changes.
1. Run `grunt buildcontrol:pages`. It will automatically push the changes to GitHub pages.
1. Open https://st-team5.github.io/LiveBetterClient/ to verify that everything is OK there as well.

Build the project manually
--------------------------
Just run `grunt` with no arguments. After a few seconds, the build output will be in `dist/`.

Run tests manually
------------------
Run `grunt test`. The test will run PhantomJS using Karma.
