
# codemirror

  a syntax highlighting editor for browsers

## Installation

    $ component install benatkin/codemirror
    $ component install benatkin/codemirror-mode-javascript

## API

First, create a new directory and run the above installation commands. Then run `component build`. Now you're ready to write some code.

Stick this in `demo.js`:

    var codemirror = require('codemirror');
    require('codemirror-mode-javascript');
    var textarea = getElementById('source');
    codemirror.fromTextArea(textarea, {
      mode: 'javascript'
    });

And put this in `demo.html`:

    <html>
      <head>
        <title>CodeMirror JavaScript demo</title>
        <link rel="stylesheet" type="text/css" href="build/build.css">
        <script src="build/build.js"></script>
        <script src="src/build.js"></script>
        <script src="demo.js"></script>
      </head>
    </html>

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
