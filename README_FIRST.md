## About this theme
---
This is a fork of the excellent [Roots Sage theme](https://roots.io/sage/) with features I frequently use:

- linting already added
  - See [Adding ESLint, Prettier, and Stylelint](https://roots.io/sage/docs/adding-linting/)
- Roots Acorn
  - See [Installing Acorn](https://roots.io/acorn/docs/installation/)
- [ACF Composer](https://github.com/Log1x/acf-composer)
  - For creating fields, blocks, widgets and option pages using [ACF Builder](https://github.com/stoutlogic/acf-builder)
- [Extended CPTs](https://github.com/johnbillion/extended-cpts#extended-cpts)
  - To quickly build custom post types and taxonomies
- Blade icons
  - See [How to use blade-icons](https://roots.io/sage/docs/use-blade-icons/)

> __IMPORTANT__
> 
> This fork may not be up-to-date with the official Roots Sage repository and each project based on Sage would likely be different and unique. __Head over to (https://github.com/roots/sage) for the best possible start for your project__.

## Using this theme
---
1. Clone this repo into your own theme folder
```sh
$ git clone git@github.com:metamezzo/sage.git my-sage-starter
```

2. Install theme
```sh
$ cd my-sage-starter
```

```sh
$ composer install
```

```sh
$ yarn
```

3. Edit `bud.config.js` - app.setPublicPath - example: `'/wp-content/themes/my-sage-starter/public/'`

4. Edit `style.css`

5. Replace text domain `'sage'` \(optional\)

6. Replace `screenshot.png`  \(optional\)


## For more info
---
Continue with the [Roots Sage README](README.md) and the [online documentation](https://roots.io/sage/docs/configuration/).
