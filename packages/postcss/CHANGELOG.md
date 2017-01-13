# @webpack-blocks/postcss - Changelog

## 0.4.0

- No changes (but `lerna` wants to bump the block's version anyway)

## 0.3.2

- Bug fix: PostCSS plugin configuration now works with webpack 2 ([#68](https://github.com/andywer/webpack-blocks/issues/68))

## 0.3.1

- Supporting custom PostCSS options now (`parser`, `stringifier`, `syntax`)

## 0.3.0

- Adapted to new API: Using `context` now

## 0.2.0

- Fix loader order issue
- Upgraded to postcss-loader v1.2.0 which supports reading the `postcss.config.js` file

## 0.1.1

- `loaders: [ 'postcss' ]` => `loaders: [ 'postcss-loader' ]`

## 0.1.0

Initial release.
