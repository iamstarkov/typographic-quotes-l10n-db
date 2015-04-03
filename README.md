# typographic-quotes-l10n-db

[![NPM version][npm-image]][npm-url]
[![Dependency Status][depstat-image]][depstat-url]
[![DevDependency Status][depstat-dev-image]][depstat-dev-url]

> Raw data about typographic quotes

Raw data about typographic quotes per language from the [appropriate wikipedia
page][wiki]. Language codes are using [ISO 639][iso] standard.

[wiki]: https://en.wikipedia.org/wiki/Quotation_mark#Summary_table_for_all_languages
[iso]: https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes


## Install

```sh
npm install --save typographic-quotes-l10n-db
```


## Usage

Pass language code and `quotesDB` will return string with 4 symbols. First two
are primary quotes, second ones are secondary.

```js
var quotesDB = require('typographic-quotes-l10n-db');

quotesDB('zh-Hans'); // “”‘’   Chinese, simplified
quotesDB('en-uk');   // ‘’“”   English, UK
quotesDB('en-us');   // “”‘’   English, US; English, Canada
quotesDB('ru');      // «»„“   Russian
quotesDB('da');      // »«›‹   Danish
quotesDB('sv');      // ””’’   Swedish
```


## License

MIT © [Vladimir Starkov](http://vstarkov.com/)

[npm-url]: https://npmjs.org/package/typographic-quotes-l10n-db
[npm-image]: http://img.shields.io/npm/v/typographic-quotes-l10n-db.svg

[depstat-url]: https://david-dm.org/matmuchrapna/typographic-quotes-l10n-db
[depstat-image]: https://david-dm.org/matmuchrapna/typographic-quotes-l10n-db.svg

[depstat-dev-url]: https://david-dm.org/matmuchrapna/typographic-quotes-l10n-db
[depstat-dev-image]: https://david-dm.org/matmuchrapna/typographic-quotes-l10n-db/dev-status.svg
