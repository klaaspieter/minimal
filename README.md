# Minimal

A very minimal blogging theme inspired by https://thebestmotherfucking.website/.

# Installation

```
git clone https://github.com/klaaspieter/minimal
```

# Developing

Start the bundled ghost blog with minimal as the default theme:

```
cd ghost
ghost start
```

Use nodemon if you want ghost to be restarted automatically:
```
cd ghost
nodemon current/index.js --watch content/themes/minimal --ext hbs,js,css
```
