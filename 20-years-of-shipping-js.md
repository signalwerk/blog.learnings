## Accessing keys is hard
```js
// es3
var hello = x.y.z
var hello = x && x.y && x.y.z

// later
var hello = _.get(x, 'y.z')

// today
const hello = x?.y?.z
```

## Recursion
* it's hard

## from class to function 
* where does the stat life
