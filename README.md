# Simple Twitter Shadowban Checker
v. 1.0 beta

This is a simple and quick webapp that crowls Twitter's search page to discover if a particular user has been shadowbanned.
Since the method is based on a 3rd party web page scan, it's not 100% reliable.

It should be said also that Twitter does not mention the practice of shadowbanning users anywhere. Nonetheless some users do not appear in search results and they're interactions are not notified to other users.
Many people think this is an obscure issue and that it should be reported.

## Recommendations
* If you don't know what shadowban is, a web browser and a search engine are all you need.
* If you think this app should have been done better, do it.

## How does it work
Apparently shadowbanning is not active in Twitter's public API. For this reason this app crowls and scans directly the search page on Twitter's web site, like a person, to discover if user's tweets are displayed.  To avoid problems with CORS a very simple php proxy is used.

## License
This application is under MIT license with addendum (see below)

Copyright (C) 2016

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE X CONSORTIUM BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
__

Addendum

Except as contained in this notice, the whole appllication and the name of the Christiano Presutti (@xho) shall not be used in advertising or otherwise to promote the sale, use or other dealings in this Software without prior written authorization from the author.
