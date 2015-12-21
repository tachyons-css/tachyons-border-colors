# tachyons-border-colors 2.2.0

Performance based css module.

#### Stats

581 | 58 | 58
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

   COLORS

*/
/* variables */
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
.b--white-10 { border-color: hsla( 0, 0, 100%, .1 ); }
.b--white-25 { border-color: hsla( 0, 0, 100%, .25 ); }
.b--white-50 { border-color: hsla( 0, 0, 100%, .5 ); }
.b--white-75 { border-color: hsla( 0, 0, 100%, .75 ); }
.b--black-10 { border-color: hsla( 0, 0, 0, .1 ); }
.b--black-25 { border-color: hsla( 0, 0, 0, .25 ); }
.b--black-50 { border-color: hsla( 0, 0, 0, .5 ); }
.b--black-75 { border-color: hsla( 0, 0, 0, .75 ); }
.b--blue { border-color: #0074D9; }
.b--light-blue { border-color: #64a8ff; }
.b--lightest-blue { border-color: #a2dfff; }
.b--dark-blue { border-color: #0045a1; }
.b--darkest-blue { border-color: #002f86; }
.b--yellow { border-color: #fff93c; }
.b--light-yellow { border-color: #fffa60; }
.b--lightest-yellow { border-color: #fffca6; }
.b--dark-yellow { border-color: #e2c100; }
.b--darkest-yellow { border-color: #c4a600; }
.b--orange { border-color: #FF851B; }
.b--light-orange { border-color: #ffa942; }
.b--lightest-orange { border-color: #ffc55d; }
.b--dark-orange { border-color: #d05e00; }
.b--darkest-orange { border-color: #b14400; }
.b--red { border-color: #d82c2c; }
.b--light-red { border-color: #f94f44; }
.b--lightest-red { border-color: #ff6c5c; }
.b--dark-red { border-color: #bd001a; }
.b--darkest-red { border-color: #9d0003; }
.b--teal { border-color: #27bfa8; }
.b--light-teal { border-color: #4eddc5; }
.b--lightest-teal { border-color: #6ffae0; }
.b--dark-teal { border-color: #25a28f; }
.b--darkest-teal { border-color: #008876; }
.b--green { border-color: #3D9970; }
.b--light-green { border-color: #5ab48a; }
.b--lightest-green { border-color: #75d0a4; }
.b--dark-green { border-color: #1e7f58; }
.b--darkest-green { border-color: #006540; }
.b--pink { border-color: #F012BE; }
.b--light-pink { border-color: #ff57e8; }
.b--lightest-pink { border-color: #ff81ff; }
.b--dark-pink { border-color: #d100a3; }
.b--darkest-pink { border-color: #b20088; }
.b--purple { border-color: #980bc6; }
.b--light-purple { border-color: #b536e2; }
.b--lightest-purple { border-color: #d355ff; }
.b--dark-purple { border-color: #7b00a9; }
.b--darkest-purple { border-color: #5f008e; }
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

