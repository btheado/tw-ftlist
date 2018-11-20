This [Tiddlywiki](http://tiddlywiki.com) plugin provides a way to quickly capture short notes and manage them in a list. It also provides a way to categorize these notes via drag and drop tagging.  See https://btheado.github.io/tw-ftlist/ for a demo and more documentation.

---

## Instructions for building from source

Install [Node](https://nodejs.org/en/download/) for your platform, then clone and build this repository:

```sh
git clone https://github.com/btheado/tw-ftlist.git
cd tw-ftlist
npm install
```

You can start the TiddlyWiki server and view a demo of the plugin:

```sh
npm run tw_start
```

Then open http://127.0.0.1:8087 in your browser.

Or you can bundle TiddlyWiki and the tw-ftlist plugin together into a single, self-modifiable html file:

```sh
npm run build:index
```

Then open the wiki/output/index.html file in your browser.

