Chrome UI bootstrap
================

[Style guide](http://roykolak.github.com/chrome-bootstrap/)

Chrome's UI stylings look pretty nice and are advancing quickly. In order to make top quanlity extensions, apps, and other one offs that look and feel like Chrome's system apps, these styles must be exposed for easy reuse.

This project aims at accomplishing this goal while keeping the scope extremely simple.

Scope
----------------

* Reusable selectors
* CSS animations
* I18n'ed properties
* Images encoded as strings

And that's it. Let's keep it simple!

Pull requests
----------------

Make sure to work in `chrome-bootstrap.less` and include a generated `chrome-bootstrap.css` file using the Less CSS compiler.

    $ npm install -g less
    $ lessc chrome-bootstrap.less > chrome-bootstrap.css

More info at [lesscss.org](http://lesscss.org/)
