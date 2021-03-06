
# KMinSer – Data serialization with minification.

This is a [Lua][lua] module that contains functions to serialize values to
strings, and deserialize these strings back to values. It is able to serialize
strings, numbers, booleans, nil values, and tables.

The serialized output is a chunk of Lua code yielding comparable values.

The module does its best to generate the most compact code possible.

See the module file for details.

## License

This module is released under a MIT-like license.
See `LICENSE.md` for details.

## Requirements

* [Lua][lua] 5.1 or above.

## Links

* Download development version: [`.zip`][devzip], [`.tar.gz`][devtgz].
* [Repository][repo] at Github.

[lua]: http://lua.org
[devzip]: https://github.com/kaeza/kminser/archive/master.zip
[devtgz]: https://github.com/kaeza/kminser/archive/master.tar.gz
[repo]: https://github.com/kaeza/lua-minser
