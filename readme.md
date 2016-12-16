# tachyons-svg 1.0.1

Tachyons module for manipulating common SVG attributes

#### Stats

2013 | 258 | 258
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-svg
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-svg
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-svg.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-svg";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-svg@1.0.1/css/tachyons-svg.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-svg">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   SVG

   Base:
     fill = fill color
     stroke = stroke color
     sw = stroke-width

   Modifiers:
     0 = 0 width stroke
     1 = 1st step in stroke-width scale
     2 = 2nd step in stroke-width scale
     3 = 3rd step in stroke-width scale
     4 = 4th step in stroke-width scale
     5 = 5th step in stroke-width scale
     6 = 6th step in stroke-width scale
     7 = 7th step in stroke-width scale

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large
*/
/* Stroke colors */
.stroke-black-90 { stroke: rgba( 0, 0, 0, .9 ); }
.stroke-black-80 { stroke: rgba( 0, 0, 0, .8 ); }
.stroke-black-70 { stroke: rgba( 0, 0, 0, .7 ); }
.stroke-black-60 { stroke: rgba( 0, 0, 0, .6 ); }
.stroke-black-50 { stroke: rgba( 0, 0, 0, .5 ); }
.stroke-black-40 { stroke: rgba( 0, 0, 0, .4 ); }
.stroke-black-30 { stroke: rgba( 0, 0, 0, .3 ); }
.stroke-black-20 { stroke: rgba( 0, 0, 0, .2 ); }
.stroke-black-10 { stroke: rgba( 0, 0, 0, .1 ); }
.stroke-black-05 { stroke: rgba( 0, 0, 0, .05 ); }
.stroke-white-90 { stroke: rgba( 255, 255, 255, .9 ); }
.stroke-white-80 { stroke: rgba( 255, 255, 255, .8 ); }
.stroke-white-70 { stroke: rgba( 255, 255, 255, .7 ); }
.stroke-white-60 { stroke: rgba( 255, 255, 255, .6 ); }
.stroke-white-50 { stroke: rgba( 255, 255, 255, .5 ); }
.stroke-white-40 { stroke: rgba( 255, 255, 255, .4 ); }
.stroke-white-30 { stroke: rgba( 255, 255, 255, .3 ); }
.stroke-white-20 { stroke: rgba( 255, 255, 255, .2 ); }
.stroke-white-10 { stroke: rgba( 255, 255, 255, .1 ); }
.stroke-black { stroke: #000; }
.stroke-near-black { stroke: #111; }
.stroke-dark-gray { stroke: #333; }
.stroke-mid-gray { stroke: #555; }
.stroke-gray { stroke: #777; }
.stroke-silver { stroke: #999; }
.stroke-light-silver { stroke: #aaa; }
.stroke-moon-gray { stroke: #ccc; }
.stroke-light-gray { stroke: #eee; }
.stroke-near-white { stroke: #f4f4f4; }
.stroke-white { stroke: #fff; }
.stroke-dark-red { stroke: #e7040f; }
.stroke-red { stroke: #ff4136; }
.stroke-light-red { stroke: #ff725c; }
.stroke-orange { stroke: #ff6300; }
.stroke-gold { stroke: #ffb700; }
.stroke-yellow { stroke: #ffd700; }
.stroke-light-yellow { stroke: #fbf1a9; }
.stroke-purple { stroke: #5e2ca5; }
.stroke-light-purple { stroke: #a463f2; }
.stroke-dark-pink { stroke: #d5008f; }
.stroke-hot-pink { stroke: #ff41b4; }
.stroke-pink { stroke: #ff80cc; }
.stroke-light-pink { stroke: #ffa3d7; }
.stroke-dark-green { stroke: #137752; }
.stroke-green { stroke: #19a974; }
.stroke-light-green { stroke: #9eebcf; }
.stroke-navy { stroke: #001b44; }
.stroke-dark-blue { stroke: #00449e; }
.stroke-blue { stroke: #357edd; }
.stroke-light-blue { stroke: #96ccff; }
.stroke-lightest-blue { stroke: #cdecff; }
.stroke-washed-blue { stroke: #f6fffe; }
.stroke-washed-green { stroke: #e8fdf5; }
.stroke-washed-yellow { stroke: #fffceb; }
.stroke-washed-red { stroke: #ffdfdf; }
.stroke-current-color { stroke: currentColor; }
/* Stroke hover colors */
.hover-stroke-black-90:hover { stroke: rgba( 0, 0, 0, .9 ); }
.hover-stroke-black-80:hover { stroke: rgba( 0, 0, 0, .8 ); }
.hover-stroke-black-70:hover { stroke: rgba( 0, 0, 0, .7 ); }
.hover-stroke-black-60:hover { stroke: rgba( 0, 0, 0, .6 ); }
.hover-stroke-black-50:hover { stroke: rgba( 0, 0, 0, .5 ); }
.hover-stroke-black-40:hover { stroke: rgba( 0, 0, 0, .4 ); }
.hover-stroke-black-30:hover { stroke: rgba( 0, 0, 0, .3 ); }
.hover-stroke-black-20:hover { stroke: rgba( 0, 0, 0, .2 ); }
.hover-stroke-black-10:hover { stroke: rgba( 0, 0, 0, .1 ); }
.hover-stroke-black-05:hover { stroke: rgba( 0, 0, 0, .05 ); }
.hover-stroke-white-90:hover { stroke: rgba( 255, 255, 255, .9 ); }
.hover-stroke-white-80:hover { stroke: rgba( 255, 255, 255, .8 ); }
.hover-stroke-white-70:hover { stroke: rgba( 255, 255, 255, .7 ); }
.hover-stroke-white-60:hover { stroke: rgba( 255, 255, 255, .6 ); }
.hover-stroke-white-50:hover { stroke: rgba( 255, 255, 255, .5 ); }
.hover-stroke-white-40:hover { stroke: rgba( 255, 255, 255, .4 ); }
.hover-stroke-white-30:hover { stroke: rgba( 255, 255, 255, .3 ); }
.hover-stroke-white-20:hover { stroke: rgba( 255, 255, 255, .2 ); }
.hover-stroke-white-10:hover { stroke: rgba( 255, 255, 255, .1 ); }
.hover-stroke-black:hover { stroke: #000; }
.hover-stroke-near-black:hover { stroke: #111; }
.hover-stroke-dark-gray:hover { stroke: #333; }
.hover-stroke-mid-gray:hover { stroke: #555; }
.hover-stroke-gray:hover { stroke: #777; }
.hover-stroke-silver:hover { stroke: #999; }
.hover-stroke-light-silver:hover { stroke: #aaa; }
.hover-stroke-moon-gray:hover { stroke: #ccc; }
.hover-stroke-light-gray:hover { stroke: #eee; }
.hover-stroke-near-white:hover { stroke: #f4f4f4; }
.hover-stroke-white:hover { stroke: #fff; }
.hover-stroke-dark-red:hover { stroke: #e7040f; }
.hover-stroke-red:hover { stroke: #ff4136; }
.hover-stroke-light-red:hover { stroke: #ff725c; }
.hover-stroke-orange:hover { stroke: #ff6300; }
.hover-stroke-gold:hover { stroke: #ffb700; }
.hover-stroke-yellow:hover { stroke: #ffd700; }
.hover-stroke-light-yellow:hover { stroke: #fbf1a9; }
.hover-stroke-purple:hover { stroke: #5e2ca5; }
.hover-stroke-light-purple:hover { stroke: #a463f2; }
.hover-stroke-dark-pink:hover { stroke: #d5008f; }
.hover-stroke-hot-pink:hover { stroke: #ff41b4; }
.hover-stroke-pink:hover { stroke: #ff80cc; }
.hover-stroke-light-pink:hover { stroke: #ffa3d7; }
.hover-stroke-dark-green:hover { stroke: #137752; }
.hover-stroke-green:hover { stroke: #19a974; }
.hover-stroke-light-green:hover { stroke: #9eebcf; }
.hover-stroke-navy:hover { stroke: #001b44; }
.hover-stroke-dark-blue:hover { stroke: #00449e; }
.hover-stroke-blue:hover { stroke: #357edd; }
.hover-stroke-light-blue:hover { stroke: #96ccff; }
.hover-stroke-lightest-blue:hover { stroke: #cdecff; }
.hover-stroke-washed-blue:hover { stroke: #f6fffe; }
.hover-stroke-washed-green:hover { stroke: #e8fdf5; }
.hover-stroke-washed-yellow:hover { stroke: #fffceb; }
.hover-stroke-washed-red:hover { stroke: #ffdfdf; }
.hover-stroke-current-color:hover { stroke: currentColor; }
/* Fill colors */
.fill-black-90 { fill: rgba( 0, 0, 0, .9 ); }
.fill-black-80 { fill: rgba( 0, 0, 0, .8 ); }
.fill-black-70 { fill: rgba( 0, 0, 0, .7 ); }
.fill-black-60 { fill: rgba( 0, 0, 0, .6 ); }
.fill-black-50 { fill: rgba( 0, 0, 0, .5 ); }
.fill-black-40 { fill: rgba( 0, 0, 0, .4 ); }
.fill-black-30 { fill: rgba( 0, 0, 0, .3 ); }
.fill-black-20 { fill: rgba( 0, 0, 0, .2 ); }
.fill-black-10 { fill: rgba( 0, 0, 0, .1 ); }
.fill-black-05 { fill: rgba( 0, 0, 0, .05 ); }
.fill-white-90 { fill: rgba( 255, 255, 255, .9 ); }
.fill-white-80 { fill: rgba( 255, 255, 255, .8 ); }
.fill-white-70 { fill: rgba( 255, 255, 255, .7 ); }
.fill-white-60 { fill: rgba( 255, 255, 255, .6 ); }
.fill-white-50 { fill: rgba( 255, 255, 255, .5 ); }
.fill-white-40 { fill: rgba( 255, 255, 255, .4 ); }
.fill-white-30 { fill: rgba( 255, 255, 255, .3 ); }
.fill-white-20 { fill: rgba( 255, 255, 255, .2 ); }
.fill-white-10 { fill: rgba( 255, 255, 255, .1 ); }
.fill-black { fill: #000; }
.fill-near-black { fill: #111; }
.fill-dark-gray { fill: #333; }
.fill-mid-gray { fill: #555; }
.fill-gray { fill: #777; }
.fill-silver { fill: #999; }
.fill-light-silver { fill: #aaa; }
.fill-moon-gray { fill: #ccc; }
.fill-light-gray { fill: #eee; }
.fill-near-white { fill: #f4f4f4; }
.fill-white { fill: #fff; }
.fill-transparent { fill: transparent; }
.fill-dark-red { fill: #e7040f; }
.fill-red { fill: #ff4136; }
.fill-light-red { fill: #ff725c; }
.fill-orange { fill: #ff6300; }
.fill-gold { fill: #ffb700; }
.fill-yellow { fill: #ffd700; }
.fill-light-yellow { fill: #fbf1a9; }
.fill-purple { fill: #5e2ca5; }
.fill-light-purple { fill: #a463f2; }
.fill-dark-pink { fill: #d5008f; }
.fill-hot-pink { fill: #ff41b4; }
.fill-pink { fill: #ff80cc; }
.fill-light-pink { fill: #ffa3d7; }
.fill-dark-green { fill: #137752; }
.fill-green { fill: #19a974; }
.fill-light-green { fill: #9eebcf; }
.fill-navy { fill: #001b44; }
.fill-dark-blue { fill: #00449e; }
.fill-blue { fill: #357edd; }
.fill-light-blue { fill: #96ccff; }
.fill-lightest-blue { fill: #cdecff; }
.fill-washed-blue { fill: #f6fffe; }
.fill-washed-green { fill: #e8fdf5; }
.fill-washed-yellow { fill: #fffceb; }
.fill-washed-red { fill: #ffdfdf; }
.fill-current-color { fill: currentColor; }
/* Fill hover colors */
.hover-fill-black-90:hover { fill: rgba( 0, 0, 0, .9 ); }
.hover-fill-black-80:hover { fill: rgba( 0, 0, 0, .8 ); }
.hover-fill-black-70:hover { fill: rgba( 0, 0, 0, .7 ); }
.hover-fill-black-60:hover { fill: rgba( 0, 0, 0, .6 ); }
.hover-fill-black-50:hover { fill: rgba( 0, 0, 0, .5 ); }
.hover-fill-black-40:hover { fill: rgba( 0, 0, 0, .4 ); }
.hover-fill-black-30:hover { fill: rgba( 0, 0, 0, .3 ); }
.hover-fill-black-20:hover { fill: rgba( 0, 0, 0, .2 ); }
.hover-fill-black-10:hover { fill: rgba( 0, 0, 0, .1 ); }
.hover-fill-black-05:hover { fill: rgba( 0, 0, 0, .05 ); }
.hover-fill-white-90:hover { fill: rgba( 255, 255, 255, .9 ); }
.hover-fill-white-80:hover { fill: rgba( 255, 255, 255, .8 ); }
.hover-fill-white-70:hover { fill: rgba( 255, 255, 255, .7 ); }
.hover-fill-white-60:hover { fill: rgba( 255, 255, 255, .6 ); }
.hover-fill-white-50:hover { fill: rgba( 255, 255, 255, .5 ); }
.hover-fill-white-40:hover { fill: rgba( 255, 255, 255, .4 ); }
.hover-fill-white-30:hover { fill: rgba( 255, 255, 255, .3 ); }
.hover-fill-white-20:hover { fill: rgba( 255, 255, 255, .2 ); }
.hover-fill-white-10:hover { fill: rgba( 255, 255, 255, .1 ); }
.hover-fill-black:hover { fill: #000; }
.hover-fill-near-black:hover { fill: #111; }
.hover-fill-dark-gray:hover { fill: #333; }
.hover-fill-mid-gray:hover { fill: #555; }
.hover-fill-gray:hover { fill: #777; }
.hover-fill-silver :hover { fill: #999; }
.hover-fill-light-silver:hover { fill: #aaa; }
.hover-fill-moon-gray:hover { fill: #ccc; }
.hover-fill-light-gray:hover { fill: #eee; }
.hover-fill-near-white:hover { fill: #f4f4f4; }
.hover-fill-white:hover { fill: #fff; }
.hover-fill-transparent:hover { fill: transparent; }
.hover-fill-dark-red:hover { fill: #e7040f; }
.hover-fill-red:hover { fill: #ff4136; }
.hover-fill-light-red:hover { fill: #ff725c; }
.hover-fill-orange:hover { fill: #ff6300; }
.hover-fill-gold:hover { fill: #ffb700; }
.hover-fill-yellow:hover { fill: #ffd700; }
.hover-fill-light-yellow:hover { fill: #fbf1a9; }
.hover-fill-purple:hover { fill: #5e2ca5; }
.hover-fill-light-purple:hover { fill: #a463f2; }
.hover-fill-dark-pink:hover { fill: #d5008f; }
.hover-fill-hot-pink:hover { fill: #ff41b4; }
.hover-fill-pink:hover { fill: #ff80cc; }
.hover-fill-light-pink:hover { fill: #ffa3d7; }
.hover-fill-dark-green:hover { fill: #137752; }
.hover-fill-green:hover { fill: #19a974; }
.hover-fill-light-green:hover { fill: #9eebcf; }
.hover-fill-navy:hover { fill: #001b44; }
.hover-fill-dark-blue:hover { fill: #00449e; }
.hover-fill-blue:hover { fill: #357edd; }
.hover-fill-light-blue:hover { fill: #96ccff; }
.hover-fill-lightest-blue:hover { fill: #cdecff; }
.hover-fill-washed-blue:hover { fill: #f6fffe; }
.hover-fill-washed-green:hover { fill: #e8fdf5; }
.hover-fill-washed-yellow:hover { fill: #fffceb; }
.hover-fill-washed-red:hover { fill: #ffdfdf; }
.hover-fill-current-color:hover { fill: currentColor; }
/* Stroke widths */
.sw0 { stroke-width: 0; }
.sw1 { stroke-width: .125rem; }
.sw2 { stroke-width: .25rem; }
.sw3 { stroke-width: .5rem; }
.sw4 { stroke-width: 1rem; }
.sw5 { stroke-width: 2rem; }
.sw6 { stroke-width: 4rem; }
.sw7 { stroke-width: 8rem; }
@media screen and (min-width: 30em) {
 .sw0-ns { stroke-width: 0; }
 .sw1-ns { stroke-width: .125rem; }
 .sw2-ns { stroke-width: .25rem; }
 .sw3-ns { stroke-width: .5rem; }
 .sw4-ns { stroke-width: 1rem; }
 .sw5-ns { stroke-width: 2rem; }
 .sw6-ns { stroke-width: 4rem; }
 .sw7-ns { stroke-width: 8rem; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .sw0-m { stroke-width: 0; }
 .sw1-m { stroke-width: .125rem; }
 .sw2-m { stroke-width: .25rem; }
 .sw3-m { stroke-width: .5rem; }
 .sw4-m { stroke-width: 1rem; }
 .sw5-m { stroke-width: 2rem; }
 .sw6-m { stroke-width: 4rem; }
 .sw7-m { stroke-width: 8rem; }
}
@media screen and (min-width: 60em) {
 .sw0-l { stroke-width: 0; }
 .sw1-l { stroke-width: .125rem; }
 .sw2-l { stroke-width: .25rem; }
 .sw3-l { stroke-width: .5rem; }
 .sw4-l { stroke-width: 1rem; }
 .sw5-l { stroke-width: 2rem; }
 .sw6-l { stroke-width: 4rem; }
 .sw7-l { stroke-width: 8rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

- [Alec Lomas](http://lowmess.com)

## License

ISC

