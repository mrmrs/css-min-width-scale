# css-min-width-scale 0.0.6

Css module of single purpose classes for min width scale

#### Stats

285 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-min-width-scale
```

#### With Git

```
git clone https://github.com/tachyons-css/css-min-width-scale
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-min-width-scale";
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
<link rel="stylesheet" href="path/to/module/css/css-min-width-scale">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MIN WIDTH - SCALE
*/
.mn-wi1 { min-width: 1rem; }
.mn-wi2 { min-width: 2rem; }
.mn-wi3 { min-width: 4rem; }
.mn-wi4 { min-width: 8rem; }
.mn-wi5 { min-width: 16rem; }
.mn-wi6 { min-width: 32rem; }
.mn-wi7 { min-width: 48rem; }
.mn-wi8 { min-width: 64rem; }
.mn-wi9 { min-width: 96rem; }
.mn-wi10 { min-width: 128rem; }
@media screen and (min-width: 48em) {
 .mn-wi1-ns { min-width: 1rem; }
 .mn-wi2-ns { min-width: 2rem; }
 .mn-wi3-ns { min-width: 4rem; }
 .mn-wi4-ns { min-width: 8rem; }
 .mn-wi5-ns { min-width: 16rem; }
 .mn-wi6-ns { min-width: 32rem; }
 .mn-wi7-ns { min-width: 48rem; }
 .mn-wi8-ns { min-width: 64rem; }
 .mn-wi9-ns { min-width: 96rem; }
 .mn-wi10-ns { min-width: 128rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mn-wi1-m { min-width: 1rem; }
 .mn-wi2-m { min-width: 2rem; }
 .mn-wi3-m { min-width: 4rem; }
 .mn-wi4-m { min-width: 8rem; }
 .mn-wi5-m { min-width: 16rem; }
 .mn-wi6-m { min-width: 32rem; }
 .mn-wi7-m { min-width: 48rem; }
 .mn-wi8-m { min-width: 64rem; }
 .mn-wi9-m { min-width: 96rem; }
 .mn-wi10-m { min-width: 128rem; }
}
@media screen and (min-width: 64em) {
 .mn-wi1-l { min-width: 1rem; }
 .mn-wi2-l { min-width: 2rem; }
 .mn-wi3-l { min-width: 4rem; }
 .mn-wi4-l { min-width: 8rem; }
 .mn-wi5-l { min-width: 16rem; }
 .mn-wi6-l { min-width: 32rem; }
 .mn-wi7-l { min-width: 48rem; }
 .mn-wi8-l { min-width: 64rem; }
 .mn-wi9-l { min-width: 96rem; }
 .mn-wi10-l { min-width: 128rem; }
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

MIT

