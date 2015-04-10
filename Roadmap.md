## v0.5 ##

**DONE**:
  * ~~Proxy support (via environment variable http\_proxy)~~
  * ~~Cookie support (--cookie to give the cookie)~~
  * ~~Fixing bugs in URL constructions~~

## v0.8 ##

TODO list:
  * ~~Full HTTPS support (seems to be buggy in some cases)~~ looks like it works
  * ~~Handle the `<base href="..." />` for link constructions~~
  * ~~Clean the code (refactoring)~~
  * ~~Should log external links as well~~
  * Implement a callback function that could be called for each URL
  * Regroup similar URL in output
    * for example _index.php?id=1_, _index.php?id=2_, ..., _index.php?id=42_ to become only _index.php?id=**X**_)
  * Check the HTTP header to make sure we are not requesting a binary file
  * Generate random User Agents

## v1.0 ##

TODO list:
  * Handle redirections
  * Colorize the results (like `grep --color`)
  * Stealth mode
  * ~~Parallelize HTTP requests using threads for faster results~~ can be buggy for now (use `--no-threads` option)

## v1.5 ##
TODO list:
  * HTML generation
  * Maybe an even more generic code and provide a simple crawler API, then copy our code in it (because the crawler could be useful in many other cases)