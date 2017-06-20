# clj-grobid

A clojure library to make working with GROBID a little easier.

## About GROBID

[GROBID](https://github.com/kermitt2/grobid) - A machine learning software for extracting information from scholarly documents

## Usage

```
;; Install GROBID locally

git clone https://github.com/kermitt2/grobid
cd grobid
mvn install

;; Setup clj-grobid

git clone https://github.com/tuddman/clj-grobid
cd clj-grobid
lein repl
=> (require '[clj-grobid.core :as gc])
...

```

### Underlying Technology

GROBID uses a modified version of Wapiti as the default CRF (Conditional Random Fields) library.\

You can check that out [here](https://github.com/kermitt2/Wapiti)

## License

Copyright © 2017 tuddman

[GROBID is licensed under Apache v2.0](https://github.com/kermitt2/grobid/blob/master/LICENSE)

and so, so is this.

