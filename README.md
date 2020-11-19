
# Minigrid

A very simple flex based grid system with only one breakpoint (768px).

IE11 and mobile compatible. Can be combined with the [u87.css](https://github.com/Serrin/u87.css).

Latest version: 1.0.1

Date: 2020-05-12T19:16:51.793Z

There are 2 versions:
- minigrid.css (1968 byte) and minigrid.min.css (1277 byte)
- minigrid-lite.css (641 byte) and minigrid-lite.min.css (535 byte)

The Lite version doesn't contain the `.mg-col-XX` classes. The size of the cells can be set with the `flex: value;` CSS property.


## Classes

Class|Description
-----|-----------
`.mg-container`|The default container.
`.mg-row`|The row of the grid.
`.mg-col`|The cell of the row.
`.mg-nopadding`|A helper class which removes the padding in the cells.


### `.mg-col-XX` helper classes

class|size|grid 12
-----|----|---------------
`.mg-col-6`|1/16|
`.mg-col-8`||1/12
`.mg-col-12`|1/8|
`.mg-col-16`|1/6|2/12
`.mg-col-20`|1/5|
`.mg-col-25`|1/4|3/12
`.mg-col-33`|1/3|4/12
`.mg-col-40`|2/5|
`.mg-col-41`||5/12
`.mg-col-50`|1/2|6/12
`.mg-col-58`||7/12
`.mg-col-60`|3/5|
`.mg-col-66`|2/3|8/12
`.mg-col-75`|3/4|9/12
`.mg-col-80`|4/5|
`.mg-col-83`||10/12
`.mg-col-91`||11/12
`.mg-col-100`|1/1|12/12


## Samples

There are more samples in the __minigrid.html__ and __minigrid-lite.html__ files.


### With `.mg-col-XX`

````html
<div class="mg-container">
  <div class="mg-row">
    <div class="mg-col mg-col-25">left 25%</div>
    <div class="mg-col mg-col-75 mg-nopadding">right 75% without padding</div>
  </div>
</div>
````


### Without `.mg-col-XX`

````html
<div class="mg-container">
  <div class="mg-row">
    <div class="mg-col" style="flex: 1;">left 25%</div>
    <div class="mg-col mg-nopadding" style="flex: 3;">right 75% without padding</div>
  </div>
</div>
````


## License

[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

MIT License

SPDX short identifier: MIT

Copyright (c) 2020 Ferenc Czigler

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
