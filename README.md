# cryptpad-level-store

Storage API for cryptpad implemented using leveldb

## Status

Supported.

## Why?

cryptpad-level-store was written as an easier alternative to the previous datastore used by cryptpad (cryptpad-mongo-store).

Leveldb automatically creates your database if no database currently exists at the provided path.

## Install

npm install cryptpad-level-store;

## Configure

```
{
    storage: 'cryptpad-level-store',
    levelPath: './datastore.db',
}
```

## License

AGPL-3.0
