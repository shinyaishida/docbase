# docbase-query

Query DocBase memos from terminals.

## Prerequisites

This tool is developed with Python 3.8. The packages it uses are managed by
[Poetry](https://python-poetry.org/).

This tool expects two environment variables `DOCBASE_QUERY_TOKEN` and 
`DOCBASE_DOMAIN`, which are a DocBase API token and a domain name, respectively.

## Usage

```bash
$ poetry install
$ poetry run python docbase-query.py /h
```

or, if you have already install the packages required by this tool,

```bash
$ python docbase-query.py /h
```

prints the usage. Note that this tool employs `/` as the prefix of option flags,
which are `-` and/or `--` in general, because `-` is used as NOT operator in the
query syntax of DocBase.

# License

MIT

# Author

Shinya Ishida
