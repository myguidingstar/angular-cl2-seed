Angular-cl2-seed
================
A battery-included template for using AngularJS and [ChlorineJS](https://github.com/chlorinejs/chlorine/wiki).
Bootstrap customization, font-awesome and unit tests are ready to use.

Usage
=====

Install dependencies
--------------------
```bash
npm install
# install front-end stuff with bower
# https://github.com/twitter/bower
cd target
bower install
```

Live coding
-----------

Have your files watched and auto-compiled:
```
npm run-script watch
```
This will watch for changes and re-compile `*.cl2` files to Javascript.

Now open an other terminal, run testem:
```
npm run-script livetest
```

You may want not only unit tests but also the final HTML file to reload on
 update. Tools like [nodefront](http://karthikv.github.io/nodefront/) is for you:

```bash
# install nodefront if you haven't
npm install -g nodefront
cd target
nodefront serve -l/--live
```

Bootstrap
---------
A simple blue bootstrap theme is included. You can customize it with the `/less` directory.
