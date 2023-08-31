# Tap Tap Tap

![](logosmall.png)

Ubuntu Touch port of the HTML5 minigame by [MahdiF](https://github.com/MahdiF/taptaptap).

[![OpenStore](https://open-store.io/badges/en_US.png)](https://open-store.io/app/taptaptap.collaproductions)
[![](https://i.imgur.com/KIipzE8.png)](https://t.me/collaproductions)

### Building the app (Ubuntu-based distros)

Install [clickable](https://clickable-ut.dev/en/latest/install.html):

```
$ sudo add-apt-repository ppa:bhdouglass/clickable
$ sudo apt-get install clickable
```

Clone this repository and build:

```
$ git clone https://github.com/nicolascolla/taptaptap.git
$ cd taptaptap
$ clickable build
```

### Building the app for 16.04

Install [clickable](https://clickable-ut.dev/en/latest/install.html):

```
$ sudo add-apt-repository ppa:bhdouglass/clickable
$ sudo apt-get install clickable
```

Clone this repository, change the framework and build:

```
$ git clone https://github.com/nicolascolla/taptaptap.git
$ cd taptaptap
$ sed -i 's/ubuntu-sdk-20.04/ubuntu-sdk-16.04.5/' clickable.yaml
$ sed -i 's/20.04/16.04/' taptaptap.apparmor
$ clickable build
```

You can play the game on any web browser by opening taptaptap/www/index.html.

### Screenshots

![](screenshot1.png)
![](screenshot2.png)
