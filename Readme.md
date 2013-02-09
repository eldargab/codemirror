
# codemirror

  a syntax highlighting editor for browsers

## TODO

* Make some components for CodeMirror syntaxes
* Document using the syntaxes
* Make components for CodeMirror themes
* Document using the themes

## Getting Started

Check out the example to learn how to use this.

    $ cd example
    $ npm install -g component
    $ component install
    $ component build
    $ npm install -g serve
    $ serve

After running the above commands, open up http://localhost:3000/ to see it in action.

## API

    var codemirror = require('codemirror');
    codemirror.fromTextArea(textarea);

## License

Copyright (C) 2013 Ben Atkin <ben@benatkin.com>

Copyright (C) 2013 by Marijn Haverbeke <marijnh@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Please note that some subdirectories of the CodeMirror distribution
include their own LICENSE files, and are released under different
licences.
