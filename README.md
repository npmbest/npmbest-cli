# npmbest-cli
The CLI tool for https://npm.best

## Installation

```bash
$ npm install -g npmbest
```

## Usage

### Search packages

+ `$ npmbest <keyword>` e.g. `$ npmbest xss` search for "xss"
+ `$ npmbest search <keyword>` the same to `$ npmbest <keyword>`
+ `$ npmbest search <keyword> --limit <limit> --skip <skip>` e.g. `$ npmbest search xss --limit 20 --skip 0`

### Search Suggestions

+ `$ npmbest suggest <keyword>` e.g. `$ npmbest suggest xss` suggest for "xss"

## Screen

![screen](screen.png)



## License

```
The MIT License (MIT)

Copyright (c) 2015 Zongmin Lei <leizongmin@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
