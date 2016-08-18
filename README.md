# css-empty-cells 0.0.7

Css module of single purpose classes for empty cells

#### Stats

187 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-empty-cells
```

#### With Git

```
git clone https://github.com/tachyons-css/css-empty-cells
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-empty-cells";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-empty-cells">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   EMPTY CELLS
*/
.empty-show { empty-cells: show; }
.empty-hide { empty-cells: hide; }
.empty-inherit { empty-cells: inherit; }
@media screen and (min-width: 48em) {
 .empty-show-ns { empty-cells: show; }
 .empty-hide-ns { empty-cells: hide; }
 .empty-inherit-ns { empty-cells: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .empty-show-m { empty-cells: show; }
 .empty-hide-m { empty-cells: hide; }
 .empty-inherit-m { empty-cells: inherit; }
}
@media screen and (min-width: 64em) {
 .empty-show-l { empty-cells: show; }
 .empty-hide-l { empty-cells: hide; }
 .empty-inherit-l { empty-cells: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
