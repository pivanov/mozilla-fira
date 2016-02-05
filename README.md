# mozilla-fira-pack

Mozilla Fira fonts collection

## Usage

1. Install [mozilla-fira-pack](https://github.com/pivanov/mozilla-fira-pack)
```
npm install mozilla-fira-pack
```

2. Include the [mozilla-fira-pack](https://github.com/pivanov/mozilla-fira-pack) packs that you want to serve.
```js
var mozilla_fira  = require("mozilla-fira-pack");
```

3. Assuming you are using [ExpressJS](http://expressjs.com), you'll want to use the express.static middleware in order to serve up a directory with your static content (in our case: Mozilla Fira fonts)
```js
app.use('/', express.static(mozilla_fira.root));
```

4. Add a link tag to include the font CSS.
```html
<link rel="stylesheet" href="/fonts.css" />
```

You can use our CDN:
```html
<link rel="stylesheet" href="https://code.cdn.mozilla.net/fonts/fira.css" />
```

Available fonts:
* FiraMono-Bold
* FiraMono-Medium
* FiraMono-Regular
* FiraSans-Bold
* FiraSans-BoldItalic
* FiraSans-Book
* FiraSans-BookItalic
* FiraSans-Eight
* FiraSans-EightItalic
* FiraSans-ExtraBold
* FiraSans-ExtraBoldItalic
* FiraSans-ExtraLight
* FiraSans-ExtraLightItalic
* FiraSans-Four
* FiraSans-FourItalic
* FiraSans-Hair
* FiraSans-HairItalic
* FiraSans-Heavy
* FiraSans-HeavyItalic
* FiraSans-Italic
* FiraSans-Light
* FiraSans-LightItalic
* FiraSans-Medium
* FiraSans-MediumItalic
* FiraSans-Regular
* FiraSans-SemiBold
* FiraSans-SemiBoldItalic
* FiraSans-Thin
* FiraSans-ThinItalic
* FiraSans-Two
* FiraSans-TwoItalic
* FiraSans-Ultra
* FiraSans-UltraItalic
* FiraSans-UltraLight
* FiraSans-UltraLightItalic
* FiraSansCondensed-Bold
* FiraSansCondensed-BoldItalic
* FiraSansCondensed-Book
* FiraSansCondensed-BookItalic
* FiraSansCondensed-Eight
* FiraSansCondensed-EightItalic
* FiraSansCondensed-ExtraBold
* FiraSansCondensed-ExtraLight
* FiraSansCondensed-ExtraLightItalic
* FiraSansCondensed-ExtraboldItalic
* FiraSansCondensed-Four
* FiraSansCondensed-FourItalic
* FiraSansCondensed-Hair
* FiraSansCondensed-HairItalic
* FiraSansCondensed-Heavy
* FiraSansCondensed-HeavyItalic
* FiraSansCondensed-Italic
* FiraSansCondensed-Light
* FiraSansCondensed-LightItalic
* FiraSansCondensed-Medium
* FiraSansCondensed-MediumItalic
* FiraSansCondensed-Regular
* FiraSansCondensed-SemiBold
* FiraSansCondensed-SemiboldItalic
* FiraSansCondensed-Thin
* FiraSansCondensed-ThinItalic
* FiraSansCondensed-Two
* FiraSansCondensed-TwoItalic
* FiraSansCondensed-Ultra
* FiraSansCondensed-UltraItalic
* FiraSansCondensed-UltraLight
* FiraSansCondensed-UltraLightItalic


5. Set your CSS up to use the new fonts by using the "Fira Sans" and "Fira Mono" font-families.
```
body {
  font-family: 'Fira Sans', 'Fira Mono', sans-serif;
}
```

## Development Info
* Homepage: https://github.com/pivanov/mozilla-fira-pack
* Repo: https://github.com/pivanov/mozilla-fira-pack.git
* Bugs: https://github.com/pivanov/mozilla-fira-pack/issues

## Font pack author
* Pavel Ivanov
* pivanov@mozilla.com
* p.ivanov@cloudstrap.io
* http://pivanov.com
* https://github.com/pivanov
* @ivanovpavel


## License
Fonts: Licensed under version 1.1 of the SIL Open Font License
  http://scripts.sil.org/OFL

Software: Licenced under version 2.0 of the MPL
  https://www.mozilla.org/MPL/

