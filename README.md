# CacherJs
Basic JS Caching

### Usages
Use the `CCache` instance directly for Convenience.
Or, Create a new instance of the cacher using the `CreateCache()` method.

```js
CCache.Get('x');
const anotherCacher = CreateCache(); //Different caches
const yetAnother = CreateCache();
```

### Api

#### Set(key, value)
> Add/Update the value to cache using the key

#### Get(key, defaultValue)
> Get the value stored in the cache using the key. Return `defaultValue` if not found.

#### Has(key)
> Check if the cache contains any entry matching with the key

#### Remove(key)
> Remove the data from cache associated with the key

#### Clear()
> Clear all data from the Cache.
