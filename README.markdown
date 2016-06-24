# cf-loghumanize

Makes the [Steno JSON format](https://github.com/cloudfoundry/steno/blob/master/lib/steno/codec/json.rb) of the [CF logs](https://docs.cloudfoundry.org/running/managing-cf/logging.html) a bit more human-readable.

Requires [jq](https://stedolan.github.io/jq/).

# Invocation

```
cat bits-service.log | path/to/cf-loghumanize
```

# Alternatives

* [steno-prettify](https://github.com/cloudfoundry/steno/blob/master/bin/steno-prettify)
* Train your brain to parse JSON
