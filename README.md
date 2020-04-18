# trakt-importer
Python scripts for importing watched history to trakt

## How I'm thinking about this
Components:
* Miso SQL JSON dump extractor &rarr; Python object
* Miso JSON dump extractor &rarr; Python object
* validator: match Python objects against [trakt search API](https://trakt.docs.apiary.io/#reference/search/text-query/get-text-query-results) to get accurate metadata
* [import to trakt history](https://trakt.docs.apiary.io/#reference/sync/add-to-history/add-items-to-watched-history)


Probably leverage [trakt.py](https://github.com/fuzeman/trakt.py)
