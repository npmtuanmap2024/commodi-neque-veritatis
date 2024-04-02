# @npmtuanmap2024/commodi-neque-veritatis
[![Travis CI](https://travis-ci.org/simonepri/@npmtuanmap2024/commodi-neque-veritatis.svg?branch=master)](https://travis-ci.org/simonepri/@npmtuanmap2024/commodi-neque-veritatis) [![Codecov](https://img.shields.io/codecov/c/github/simonepri/@npmtuanmap2024/commodi-neque-veritatis/master.svg)](https://codecov.io/gh/simonepri/@npmtuanmap2024/commodi-neque-veritatis) [![npm](https://img.shields.io/npm/dm/@npmtuanmap2024/commodi-neque-veritatis.svg)](https://www.npmjs.com/package/@npmtuanmap2024/commodi-neque-veritatis) [![npm version](https://img.shields.io/npm/v/@npmtuanmap2024/commodi-neque-veritatis.svg)](https://www.npmjs.com/package/@npmtuanmap2024/commodi-neque-veritatis) [![npm dependencies](https://david-dm.org/simonepri/@npmtuanmap2024/commodi-neque-veritatis.svg)](https://david-dm.org/simonepri/@npmtuanmap2024/commodi-neque-veritatis) [![npm dev dependencies](https://david-dm.org/simonepri/@npmtuanmap2024/commodi-neque-veritatis/dev-status.svg)](https://david-dm.org/simonepri/@npmtuanmap2024/commodi-neque-veritatis#info=devDependencies)

> 🔎 Get the OpenStreetMap relation id from a country code.

## Install

```
$ npm install --save @npmtuanmap2024/commodi-neque-veritatis
```

## Usage

```js
const osmCountries = require('@npmtuanmap2024/commodi-neque-veritatis');

osmCountries.get('ITA');
// => '365331'

osmCountries.get('USA');
// => '148838'
```

## API

<a name="get"></a>

## get(code) ⇒ <code>string</code>
Converts an alpha-3 iso 3166-1 code to its corrispective relation id on OSM.

**Returns**: <code>string</code> - OSM relation id of the given country.  

| Param | Type | Description |
| --- | --- | --- |
| code | <code>string</code> | Alpha-3 iso 3166-1 country code. |

<a name="map"></a>

## map() ⇒ <code>object</code>
Returns a map from alpha-3 iso 3166-1 codes to theyr corrispective relation
ids on OSM.

**Returns**: <code>object</code> - Map of all OSM relation ids.  

## Authors
* **Simone Primarosa** - [simonepri](https://github.com/simonepri)

See also the list of [contributors](https://github.com/npmtuanmap2024/commodi-neque-veritatis/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
