# HTML Canvas Gauges v2.0

[![Build Status](https://travis-ci.org/Mikhus/canv-gauge.svg?branch=v2.0.0)](https://travis-ci.org/Mikhus/canv-gauge) ![Test Coverage](https://rawgit.com/Mikhus/canv-gauge/v2.0.0/test-coverage.svg) ![Documentation Coverage](https://rawgit.com/Mikhus/canv-gauge/v2.0.0/docs-coverage.svg) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/Mikhus/canv-gauge/v2.0.0/LICENSE)

[![Canvas Gauges](https://raw.githubusercontent.com/Mikhus/blob/master/gauges.png)](https://rawgit.com/Mikhus/canv-gauge/v2.0.0/examples/component.html)

<!-- toc -->

- [Installation](#installation)
- [Documentation](#documentation)
- [Sponsored By](#sponsored-by)
- [License](#license)

<!-- tocstop -->

This is tiny implementation of highly configurable gauge using pure JavaScript and HTML5 canvas.
No dependencies. Suitable for IoT devices because of minimum code base.

## Installation

Canvas gauges can be simply installed using npm package manager. Depending on your needs there is possibility to install whole gauge library or only that part you really need for your project.
To install the whole library, run:

    $ npm install canv-gauge

If you only need the exact type of the gauge it can be installed using the appropriate npm tag. Currently the following gauges are supported: linear, radial.

To install only linear gauge, run:

    $ npm install canv-gauge@linear

To install only radial gauge, run:

    $ npm install canv-gauge@radial

This strategy useful only if you need to minimize your code base and plan to use ONLY a specific gauge type. If you need to use various gauge types in your project it is recommended to use whole gauge package.

(More...)[http://mikhus.github.io/canv-gauge/documentation/user-guide/#installing]

## Documentation

You can find complete docs on the canvas gauges web-site:

 * [Quick Start Guide](http://mikhus.github.io/canv-gauge/documentation/getting-started/)
 * [Complete User Guide](http://mikhus.github.io/canv-gauge/documentation/user-guide/)
 * [Developer's Docs](http://mikhus.github.io/canv-gauge/documentation/api/)
 * [Examples](http://mikhus.github.io/canv-gauge/documentation/examples/)

## Sponsored By

[![Lohika](http://www.lohika.com/wp-content/themes/gridalicious/images/lohika_full.svg)](http://www.lohika.com/)

## License

This code is subject to [MIT](https://raw.githubusercontent.com/Mikhus/canv-gauge/v2.0.0/LICENSE) license.
