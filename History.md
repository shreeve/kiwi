
0.2.0 / 2010-03-22
==================

  * Added package.json
  * Added `$ kiwi stats`
  * Added subcommand command help via `$ kiwi help COMMAND`. Closes #52
  * Fixed; Installing kiwi to ~/.node_libraries due to recent node change

0.1.0 / 2010-03-11
==================

  * Kiwi server hosting is now provided by Slicehost! woot!
  * Fixed default version, ">= 0.0.1" not "> 0.0.1"
  * Fixed bug preventing build commands from working when NOT the last line
  * Fixed; now building after resolving dependencies. Closes #118
  * Changed; installing to /usr/local/bin
  * Removed `kiwi update self` ... use `kiwi update` or `kiwi install kiwi`
  * Server: Added download count to GET /search
  * Server: Added seed descriptions to GET /search

0.0.1 / 2010-03-05
==================

  * Initial release
