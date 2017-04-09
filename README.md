# lo-gravity.

Lodash-inspired library for Gravity language

### Status: WIP, implementation *may* be naive and contain duplication and/or errors

Currently implemented:
```
Lo.every(collection, iteratee)
Lo.find(collection, iteratee)
Lo.map(collection, iteratee)
```

Example:
```
var list = [true, false, [], [:], "bar", 33, 42];

// find 33. silly but whatever
var result = Lo.find(list, func(item) {
  return item == 33;
});
```
