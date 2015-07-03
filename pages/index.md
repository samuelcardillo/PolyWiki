# PolyWiki

Hi! Welcome on **PolyWiki** , a static markdown language page displayer quickly made on **Polymer**. This project comes from an idea and was created within an hour just to serve as an example by cloning the concept of **MDWiki**.

It has a responsive template done with Material Design elements AND *it work offline*.

## How can I use it ?

In order to run it you'll need to fetch some dependencies.

* Install [Bower](http://bower.io/):

```sh
$ [sudo] npm install -g bower 
```

* Install local dependencies:

```sh
$ bower install
```

* Put everything in the folder of your webspace
* **Change the variable `app.pathUrl` in `elements/routing.html` if PolyWiki is not in the racine !**

## How to use it ?

* Add the `.md` file in the folder named `pages`
* Change the file `app.js` to put your pages in the variable `app.pages`.