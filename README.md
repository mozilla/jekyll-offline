# jekyll-offline
[oghliner](https://github.com/mozilla/oghliner) supported plug-in for offlining Jekyll sites.

## Prerequisites
Ensure your version of Jekyll is `3.x.x` and you have oghliner installed as cli:
```
$ npm install -g oghliner
```

## Install
Copy the file `jekyll-offline.rb` that you'll find in the repository to your `_plugins` folder inside your Jekyll source location. If the folder does not exist,create it first.

## Usage
Add the tag `{% offline_manager %}` to your `head.html` _include_ (or wherever you choose) to link the proper scripts.
