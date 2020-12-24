# Grunt Starter :cherry_blossom:

## A quick `gruntfile.js` for new projects

### Dependencies

-   grunt
-   grunt-cli

### Dev Dependencies

`diff` is an outdated dependency that will be flagged by Github as a vulnerability.

-   diff
-   node-sass
-   grunt-sass
-   grunt-contrib-concat
-   grunt-contrib-uglify
-   grunt-autoprefixer
-   grunt-contrib-watch
-   grunt-contrib-connect

---

### Getting Started

```bash
npm init -y

npm i grunt grunt-cli

npm i -D diff node-sass grunt-sass grunt-contrib-concat grunt-contrib-uglify grunt-autoprefixer grunt-contrib-watch grunt-contrib-connect
```

---

### `.gitignore`

```git
node_modules
tmp
.tmp
.npm-debug.log
*.sass-cache
*.css.map
*.min.js.map
```

---

### Live Reload

Listens on `port: 8000` by default

---

### Edit Folders

```
components/
|__ scripts/
    |__ script.js
    |__ your_scripts.js

|__ scss/
    |__ _your_partials.scss
    |__ _main.scss
    |__ styles.scss
```

### Compiled Folders

---

```
dist/
|__ js/
    |__ scripts.js
    |__ scripts.min.js
    |__ scripts.min.js.map

|__ css/
    |__ styles.css
    |__ styles.map.css
```

Cheers!  
Angela :two_hearts:
