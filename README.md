# CSS EMPTY CELLS

  Mobile-first classes for css-empty-cells.
  Set the desired css-empty-cells on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-empty-cells
```
View on [npm](https://www.npmjs.org/package/css-empty-cells)


## File Size

686B empty-cells.css
527B empty-cells.min.css
164B minified and gzipped

## The Code
```
.empty-show {     empty-cells: show; }
.empty-hide {     empty-cells: hide; }
.empty-inherit {  empty-cells: inherit; }

@media screen and (min-width: 48em) {
  .empty-show-ns {     empty-cells: show; }
  .empty-hide-ns {     empty-cells: hide; }
  .empty-inherit-ns {  empty-cells: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .empty-show-m {     empty-cells: show; }
  .empty-hide-m {     empty-cells: hide; }
  .empty-inherit-m {  empty-cells: inherit; }
}

@media screen and (min-width: 64em)  {
  .empty-show-l {     empty-cells: show; }
  .empty-hide-l {     empty-cells: hide; }
  .empty-inherit-l {  empty-cells: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

