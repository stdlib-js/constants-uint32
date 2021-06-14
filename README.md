<!--

@license Apache-2.0

Copyright (c) 2021 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Constants

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> 32-bit unsigned integer mathematical constants.

<section class="installation">

## Installation

```bash
npm install @stdlib/constants-uint32
```

</section>

<section class="usage">

## Usage

```javascript
var constants = require( '@stdlib/constants-uint32' );
```

#### constants

32-bit unsigned integer mathematical constants.

```javascript
var c = constants;
// returns {...}
```

<!-- <toc pattern="*" > -->

<div class="namespace-toc">

-   <span class="signature">[`MAX`][@stdlib/constants/uint32/max]</span><span class="delimiter">: </span><span class="description">maximum unsigned 32-bit integer.</span>
-   <span class="signature">[`NUM_BYTES`][@stdlib/constants/uint32/num-bytes]</span><span class="delimiter">: </span><span class="description">size (in bytes) of a 32-bit unsigned integer.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var constants = require( '@stdlib/constants-uint32' );

console.log( objectKeys( constants ) );
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-uint32.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-uint32

[test-image]: https://github.com/stdlib-js/constants-uint32/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/constants-uint32/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-uint32/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-uint32?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-uint32
[dependencies-url]: https://david-dm.org/stdlib-js/constants-uint32/main

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-uint32/main/LICENSE

<!-- <toc-links> -->

[@stdlib/constants/uint32/max]: https://github.com/stdlib-js/constants-uint32-max

[@stdlib/constants/uint32/num-bytes]: https://github.com/stdlib-js/constants-uint32-num-bytes

<!-- </toc-links> -->

</section>

<!-- /.links -->