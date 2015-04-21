# ID Generator 0.0.1
Generate id for collection with or without prefix.
### Install
```js
meteor add theara:id-generator
```
### Usage
```js
// idGenerator.gen(collection, field, length);
var id = idGenerator.gen(CustomerCollection, '_id', 3); // 001, 002

// idGenerator.genWithPrefix(collection, field, prefix, length);
var id = idGenerator.genWithPrefix(CustomerCollection, '_id', 'A', 3); // A-001, A-002
```
### Changelog
- v 0.0.1 (2014-04-21)
    - init
