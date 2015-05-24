# Casper (outofscope.com)

Variant of the default theme for [Ghost](http://github.com/tryghost/ghost/).

This version contains code specific to the [Out of Scope](http://www.outofscope.com) blog (analytics).

# Merging TryGhost/Casper

First, if you haven't set the *upstream* remote yet, you need to set it to point to TryGhost/Casper.

```
$ git remote add upstream git@github.com:TryGhost/Casper.git
```

Once the *upstream* remote is setup, fetch the changes and merge them.

```
# Fetch the latest changes from TryGhost/Casper (upstream remote)
$ git fetch upstream

# Merge master from upstream
$ git merge upstream/master master
```

To download, visit the [releases](https://github.com/TryGhost/Casper/releases) page.

## Copyright & License

Copyright (c) 2013-2015 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
