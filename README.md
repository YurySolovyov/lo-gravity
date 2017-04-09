# lo-gravity.

Lodash-inspired library for Gravity language

### Status: WIP, implementation *may* be naive and contain duplication and/or errors

Currently implemented:
```
Lo.every(collection, iteratee)
Lo.find(collection, iteratee)
Lo.map(collection, iteratee)
```

## Usage

Just `#include "lo.gravity"`:

```
#include "lo.gravity"
```
in our case it is more like this though:

```
#include "./src/lo.gravity"
```

Example:
```
#include "./src/lo.gravity"

func main() {
  var list = [true, false, [], [:], "bar", 33, 42];

  // find String
  var result = Lo.find(list, func(item) {
    return item is String;
  });

  System.print(result); // -> "bar"
}
```
