![Angular Miniscroll](http://miniscroll.rogerluizm.com.br/fb.jpg)

Angular Miniscroll is a fork of little library for touch and desktop scrollbar application - Miniscroll-JS. if you found bugs send it to anton@trackduck.com or send to <a href="https://github.com/shauchenka/Angular-Miniscroll/issues?page=1&state=open">issue</a> page

_version 0.1_

### Include miniscroll.js into your page:

<pre>
&lt;script src="miniscroll.js"&gt;&lt;/script&gt;
</pre>

***

### Include the html tag and add id or class::

<pre>
&lt;div class="scroller"&gt;
     // text here
&lt;/div&gt;
</pre>

***

### CSS of the div ".scroller"::
<pre>
.scroller {
     width: 400px;
     height: 300px;
     overflow: hidden;
}
</pre>

***

### Initialize the miniscroll:
<pre>
new Miniscroll(".scroller", {
     axis: "y",
     size: 10,
     sizethumb: "auto",
     thumbColor: "#0e5066",
     trackerColor: "#1a8bb2"
 });
</pre>

***


### Change the color and aparence for all miniscroll class:
<pre>
.miniscroll-thumb {
     background-color: #0e5066 !important;
}

.miniscroll-tracker {
    background-color: #1a8bb2 !important;
}
</pre>

***

### Change the color and aparence for a unique miniscroll id:
<pre>
&#35;miniscroll-target .miniscroll-thumb {
    background-color: #0e5066 !important;
}

&#35;miniscroll-target .miniscroll-tracker {
    background-color: #1a8bb2 !important;
}
</pre>

***

### List of parameters:
**axis:*
_axle of scrollbar ex: "y" ou "x"_<br />
**size:**
_the width of scrollbar ex: 10_<br />
**sizethumb:**
_o tamanho do thumb ex: 100 ou "auto"_<br />
**thumbColor:**
_the size of thumb ex: "#0e5066"_<br />
**trackerColor:**
_color of fund of tracker ex: "#1a8bb2"_<br />
**scrollbarSize:**
_size of scrollbar, you can set a size fix to scrollbar it ex: 300 this had left scrollbar with the height of 300px_<br />
**isKeyEvent:**
_Add arrow key event, by default is true_<br />
**turnOffWheel:**
_toggle on or off a mousewheel event, by default turnOffWheel is true_


***



### The MIT License (MIT)

Copyright (c) <year> <copyright holders>

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



