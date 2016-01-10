# overloaded

No time to explain. Code is worth a thousand words.

## Installation

```sh
$ npm install n2liquid/node-overloaded
```

## Example usage

```js
let overloaded = require('overloaded');

function scroll() {
    let args = overloaded(arguments, {
        1: ['y'],
        2: ['x', 'y'],
    });

    args.x = args.x || 0;

    // Scroll something to (x, y).
}
```

## License

![](https://www.gnu.org/graphics/agplv3-155x51.png)

overloaded is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

## Exclusion of warranty

overloaded is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

A copy of AGPLv3 can be found in [COPYING.](COPYING)
