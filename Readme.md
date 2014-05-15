
# npub

  Publish json messages to NSQ.

## Installation

```
$ npm install -g npub
```

## Usage

```

  Usage: npub [options] <topic> <msg>

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
    --nsqd <addr>  nsqd address [:4150]

```

## Example

```sh
$ npub red-range '{ "from":"2013-02-01", "to":"2014-01-01" }'
$ npub --nsqd :5001 red-range '{ "from":"2013-02-01", "to":"2014-01-01" }'
```

# License

  MIT