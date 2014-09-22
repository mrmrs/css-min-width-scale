# CSS MIN WIDTH SCALE

  Mobile-first classes for css-min-width-scale.
  Set the desired css-min-width-scale on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-min-width-scale
```
View on [npm](https://www.npmjs.org/package/css-min-width-scale)


## File Size

1.5K min-width-scale.css
1.1K min-width-scale.min.css 
239B minified and gzipped

## The Code
```
.mn-wi1  {  min-width: 1rem; }
.mn-wi2  {  min-width: 2rem; }
.mn-wi3  {  min-width: 4rem; }
.mn-wi4  {  min-width: 8rem; }
.mn-wi5  {  min-width: 16rem; }
.mn-wi6  {  min-width: 32rem; }
.mn-wi7  {  min-width: 48rem; }
.mn-wi8  {  min-width: 64rem; }
.mn-wi9  {  min-width: 96rem; }
.mn-wi10 {  min-width: 128rem; }

@media screen and (min-width: 48em) {
  .mn-wi1-ns  {  min-width: 1rem; }
  .mn-wi2-ns  {  min-width: 2rem; }
  .mn-wi3-ns  {  min-width: 4rem; }
  .mn-wi4-ns  {  min-width: 8rem; }
  .mn-wi5-ns  {  min-width: 16rem; }
  .mn-wi6-ns  {  min-width: 32rem; }
  .mn-wi7-ns  {  min-width: 48rem; }
  .mn-wi8-ns  {  min-width: 64rem; }
  .mn-wi9-ns  {  min-width: 96rem; }
  .mn-wi10-ns {  min-width: 128rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .mn-wi1-m  {  min-width: 1rem; }
  .mn-wi2-m  {  min-width: 2rem; }
  .mn-wi3-m  {  min-width: 4rem; }
  .mn-wi4-m  {  min-width: 8rem; }
  .mn-wi5-m  {  min-width: 16rem; }
  .mn-wi6-m  {  min-width: 32rem; }
  .mn-wi7-m  {  min-width: 48rem; }
  .mn-wi8-m  {  min-width: 64rem; }
  .mn-wi9-m  {  min-width: 96rem; }
  .mn-wi10-m {  min-width: 128rem; }
}

@media screen and (min-width: 64em)  {
  .mn-wi1-l  {  min-width: 1rem; }
  .mn-wi2-l  {  min-width: 2rem; }
  .mn-wi3-l  {  min-width: 4rem; }
  .mn-wi4-l  {  min-width: 8rem; }
  .mn-wi5-l  {  min-width: 16rem; }
  .mn-wi6-l  {  min-width: 32rem; }
  .mn-wi7-l  {  min-width: 48rem; }
  .mn-wi8-l  {  min-width: 64rem; }
  .mn-wi9-l  {  min-width: 96rem; }
  .mn-wi10-l {  min-width: 128rem; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

