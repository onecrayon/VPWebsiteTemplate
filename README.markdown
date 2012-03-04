# VoodooPad 5 website template, v1.0

This is the template that I use to easily manage a static website using [VoodooPad 5](http://flyingmeat.com/voodoopad/). VoodooPad 5 is a good fit for your website if:

1. You need a static site
2. That is simple enough to use a flat hierarchy
3. And only has one page template (or minor variations on a single template)

For instance, I use VoodooPad for an app documentation site, but wouldn't want to use it for my blog.

This template is setup to use Markdown for basic styling. It would probably be possible to do the same with rich text, but the scripts here will not work right if you do.

## Installation

**Requires VoodooPad 5 beta, build 3602 or greater**

To install, either clone this repo or [download here](https://github.com/onecrayon/VPWebsiteTemplate/zipball/master). You can then open the VP5WebsiteTemplate.vpdoc file in VoodooPad 5 and go from there. The file itself contains full documentation for how to use it.

## Features

* Highly configurable by modifying some variables in a simple Javascript page (you can disable or modify every feature listed here)
* Automatically renames new pages with URL-friendly names
* Automatically creates breadcrumbs based on page tags
* Copies assets (images, CSS, and Javascript) into folders
* Supports MarkdownExtra-style header IDs for easier same page navigation links:
  
        ## My header    {#header-ID}
* Automatically strips out nested links if VoodooPad and Markdown linking styles come into conflict
* Converts `->` and `=>` into `&rarr;` entities
* Converts shortcuts using the format `` `command H` `` into special HTML (for easier styling as opposed to plain code blocks)
* Fixes paragraphs wrapping `<aside>` elements (since Markdown doesn't support HTML5 very well)

And of course if the template doesn't do something that you want/need, you can always expand the capabilities by writing a bit of JavaScript.

## Changelog

**v1.0**

* Initial public release for VP5 beta
* Central configuration variables
* Automatic URL-friendly page names
* Automatic breadcrumbs using page tags
* And lots more!

## License

The content and scripts in this template are distributed under an MIT license. VoodooPad, the VoodooPad file format, JSTalk, and similar are all rights reserved by [Flying Meat](http://flyingmeat.com/) and Gus Mueller. This project is in no way endorsed by or affiliated with Flying Meat, so if it melts your computer or something, don't go blaming Gus.

Includes source code from the following other MIT-licensed projects:

* Python Markdown by Trent Mick  
  <https://github.com/trentm/python-markdown2>
* To Title Case by David Gouch  
  <http://individed.com/code/to-title-case/>

### The MIT license

Copyright (c) 2012 Ian Beck

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.