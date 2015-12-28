# hospital-run
Open source, modern software for charitable hospitals in the developing world.

**hospital-run** will be open-source soon

This repo for issues perpose.


## Install

1. Installing CouchDB
If you are on a Debian flavor of Linux (Ubuntu, Mint, etc.), you can install CouchDB with:
```sh
sudo apt-get install couchdb
```

On a Mac you can do:
```sh
brew install couchdb
```

2. Install the hospital-run please do the following:

```sh
npm install -g ember-cli
npm install -g bower

# Clone the source
git clone https://github.com/duyetdev/hospital-run

# Intall needed node and bower modules.
npm install
bower install

# initcouch database
init_db.sh <USERNAME> <PASSWORD>
```

3. Update `server/config.js`

4. Start
```sh
ember serve
```

Go to [http://localhost:4200/](http://localhost:4200/) in a browser and login with username `admin` and password `admin`.

# License

MIT License

Copyright (c) 2015 Van-Duyet Le

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.