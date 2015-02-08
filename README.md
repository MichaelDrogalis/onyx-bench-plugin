## onyx-core-bench-plugin

Onyx plugin for benchmarking. You probably don't want to use this.

#### Installation

In your project file:

```clojure
[onyx-bench-plugin "0.6.0-SNAPSHOT"]
```

In your peer boot-up namespace:

```clojure
(:require [onyx.plugin.bench-plugin])
```

#### Catalog entries

##### sample-entry

```clojure
{:onyx/name :http-listener
 :onyx/ident :http/listen
 :onyx/type :input
 :onyx/medium :http
 :onyx/consumption :concurrent
 :onyx/batch-size batch-size
 :onyx/doc "Reads segments from HTTP calls"}
```

#### License

Copyright © 2014 Michael Drogalis

Distributed under the Eclipse Public License, the same as Clojure.
