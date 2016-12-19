# cracker

Provide auto-completion for the crystal language ( racer like ) [WIP]

## Installation

[WIP]

## Usage
[WIP]

``` shell
cracker /path/to/crystal/source String#start

```
Output :
``` json
[
  {
    "name": "String#starts_with?(str : String)",
    "file": "/home/arnaud/workspace/repos/crystal/src/string.cr",
    "type": 2,
    "signature": "def starts_with?(str : String)"
  },
  {
    "name": "String#starts_with?(char : Char)",
    "file": "/home/arnaud/workspace/repos/crystal/src/string.cr",
    "type": 2,
    "signature": "def starts_with?(char : Char)"
  }
]
```

## Development

- [x] Allow to search using starts_with?
- [ ] Add line number to the result
- [ ] Replate type by a string
- [ ] Daemonize
- [ ] Give a file, line number and character number to complete with the context ?

## Contributing

1. Fork it ( https://github.com/TechMagister/cracker/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [TechMagister](https://github.com/TechMagister) Arnaud Fernandés - creator, maintainer