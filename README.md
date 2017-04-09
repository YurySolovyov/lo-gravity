# lo-gravity. WIP

Lodash-inspired library for Gravity language

Currently implemented:
```
Lo.find(collection, interatee)
Lo.map(collection, interatee)
```

Example:
```
var list = [true, false, [], [:], "bar", 33, 42];

// find 33. silly but whatever
var result = Lo.find(list, func(item) {
  return item == 33;
});
```
