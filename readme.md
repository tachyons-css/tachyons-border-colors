# tachyons-border-colors 3.1.1

Performance based css module.

#### Stats

389 | 35 | 35
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-border-colors
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-border-colors
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-border-colors";
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
<link rel="stylesheet" href="path/to/module/css/tachyons-border-colors">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   Tachyons
   COLOR VARIABLES

   Grayscale
   - Solids
   - Transparencies
*/
/*

   BORDER COLORS

*/
.b--black { border-color: #000; }
.b--near-black { border-color: #111; }
.b--dark-gray { border-color: #333; }
.b--mid-gray { border-color: #555; }
.b--gray { border-color: #777; }
.b--silver { border-color: #999; }
.b--light-silver { border-color: #aaa; }
.b--light-gray { border-color: #eee; }
.b--near-white { border-color: #f4f4f4; }
.b--white { border-color: #fff; }
.b--white-90 { border-color: rgba( 255, 255, 255, .9 ); }
.b--white-80 { border-color: rgba( 255, 255, 255, .8 ); }
.b--white-70 { border-color: rgba( 255, 255, 255, .7 ); }
.b--white-60 { border-color: rgba( 255, 255, 255, .6 ); }
.b--white-50 { border-color: rgba( 255, 255, 255, .5 ); }
.b--white-40 { border-color: rgba( 255, 255, 255, .4 ); }
.b--white-30 { border-color: rgba( 255, 255, 255, .3 ); }
.b--white-20 { border-color: rgba( 255, 255, 255, .2 ); }
.b--white-10 { border-color: rgba( 255, 255, 255, .1 ); }
.b--white-05 { border-color: rgba( 255, 255, 255, .05 ); }
.b--white-025 { border-color: rgba( 255, 255, 255, .025 ); }
.b--white-0125 { border-color: rgba( 255, 255, 255, .0125 ); }
.b--black-90 { border-color: rgba( 0, 0, 0, .9 ); }
.b--black-80 { border-color: rgba( 0, 0, 0, .8 ); }
.b--black-70 { border-color: rgba( 0, 0, 0, .7 ); }
.b--black-60 { border-color: rgba( 0, 0, 0, .6 ); }
.b--black-50 { border-color: rgba( 0, 0, 0, .5 ); }
.b--black-40 { border-color: rgba( 0, 0, 0, .4 ); }
.b--black-30 { border-color: rgba( 0, 0, 0, .3 ); }
.b--black-20 { border-color: rgba( 0, 0, 0, .2 ); }
.b--black-10 { border-color: rgba( 0, 0, 0, .1 ); }
.b--black-05 { border-color: rgba( 0, 0, 0, .05 ); }
.b--black-025 { border-color: rgba( 0, 0, 0, .025 ); }
.b--black-0125 { border-color: rgba( 0, 0, 0, .0125 ); }
.b--transparent { border-color: transparent; }
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

