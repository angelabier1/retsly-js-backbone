# retsly-js-backbone [![wercker status](https://app.wercker.com/status/c1c25d0ddf4917a14fd0de23e515fed6/s/ "wercker status")](https://app.wercker.com/project/bykey/c1c25d0ddf4917a14fd0de23e515fed6)

Use [Retsly](https://rets.ly/) with Backbone.

## Install

Install with [component](https://github.com/component/component):

    $ component install retsly/retsly-js-backbone

## Usage

```javascript
    var Retsly = require('retsly-backbone')
    Retsly.create('client_id', 'app_token');

    var listing = new Retsly.Models.Listing({_id: id, vendorID: vendor});

    listing.fetch({success: function (listing) {
      // do something with listing
    }});
```

## Repo Owner

[Jason Wan](http://github.com/jkhwan)

## License

(The MIT License)

Copyright (c) 2013 Retsly Software Inc <support@rets.ly>

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the 'Software'),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
