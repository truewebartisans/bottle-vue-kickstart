![bottle-vue-kickstart-main](https://cloud.githubusercontent.com/assets/11155743/24041455/9fbd99ec-0b1e-11e7-9ba0-a429a28591b0.jpg)

# Very basic kickstart Bootle kit with Vue.js

Simplify development of reactive web applications on [Bottle](http://bottlepy.org/) – lightweight WSGI micro web-framework for Python! A simple process of installing and deploying. Everything has already been done for you. Just enjoy writing your code!

## What is this?

Kickstart kit included latest version of `npm` packs:

* Axios (for make AJAX calls)
* Babel (for turn ES6 code into readable vanilla)
* Vue.js (for reactive 'em all)
* Vue-resource (for supports the Promise API on Vue)
* Webpack (for packing 'em all)

For visual design I use [Bulma](https://github.com/jgthms/bulma). This is a modern CSS framework based on Flexbox. Small and smart. If you haven't seen it before I promise – you'll like it!

## How to install?

First, clone this git repository:

```bash
$ git clone git@github.com:koddr/bottle-vue-kickstart.git
```

Second, install `npm` depencies and make build:

```bash
$ npm install
$ npm run build
```

Third, prepare your virtual environment:

```bash
$ cd bottle-vue-kickstart
$ python3 -m venv venv
$ source venv/bin/activate
```

Next, install Bottle and all extensions:

```bash
(venv) $ pip install bottle bottle-sqlalchemy
(venv) $ deactivate
```

Finally, run development server:

```bash
$ python run.py

Bottle v0.12.13 server starting up (using AutoServer())...
Listening on http://localhost:8080/
Hit Ctrl-C to quit.
...
```

### If you did everything right, then you'll see:

![Result without database](https://cloud.githubusercontent.com/assets/11155743/24043773/4befab4c-0b29-11e7-8118-183d56c8f231.png)

(Optional) Install database with example objects:

```bash
$ python install.py
```

Now, your yellow section on http://localhost:8080/ will look like this:

![Result with database](https://cloud.githubusercontent.com/assets/11155743/24043867/cf79c344-0b29-11e7-8066-8ebd83e68acb.png)

And we done!

## Developers

Development and maintenance of `Bottle Vue kickstart kit` project engaged by Vikky Shostak ([Koddr](https://koddr.me)). If you want to write a «thank you» or ask something, [use this e-mail](mailto:koddr.me@gmail.com).

## Your help

If you want help, we will be glad reviews about `Bottle Vue kickstart kit` on personal blogs (including Twitter), online media and/or specialized IT-portals. Thank you!

## License

[The MIT License (MIT)](https://github.com/koddr/bottle-vue-kickstart/blob/master/LICENSE.md)
