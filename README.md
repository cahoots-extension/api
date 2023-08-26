note: The Cahoots project has been discontinued. 

# Cahoots - RESTful API

This repository contains the API of the [cahoots.pw](http://cahoots.pw) project.

## Usage

Please note that you need a current release (2.x) of [io.js](https://iojs.org) in order to run the Cahoots RESTful API. You can start the API with:

```sh
npm start
```

## Configuration

  * `CAHOOTS_PROVIDER_OFFICIAL_SHEET_KEY`: The sheet key.
  * `CAHOOTS_PROVIDER_OFFICIAL_SYNC_INTERVAL`: The sync interval in ms. Default `(60 * 1000) * 5` (5min).
  * `CAHOOTS_PROVIDER_OFFICIAL_DATABASE_PATH`: The path to the internal official database.
  * `CAHOOTS_PROVIDER_TORIAL_API_ENDPOINT`: The endpoint of the torial API.
  * `CAHOOTS_PROVIDER_TORIAL_DATABASE_PATH`: The path to the internal torial database.
  * `CAHOOTS_PROVIDER_TORIAL_SYNC_INTERVAL`: The sync interval in ms. Default `(60 * 1000) * 60 * 24` (24h).

### Debug log messages

You can set an environment variable in order to see some debug log messages:

```sh
DEBUG=cahoots:* npm start
```

## License

The MIT License (MIT)

Copyright (c) 2014-2015 Cahoots, Germany <info@cahoots.pw>

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
