## Synopsis

This is just an example that I created to use the JavaScript API for SharePoint to read/write from an existing SharePoint list.
I wanted to have a bit more control over what I could do using the web browser and SharePoint Designer to calculate some columns, and 
ran into a situation where the out of box tools didn't do what I wanted.

This example takes values that were not available using the calculated column feature, and calculates it using JavaScript, then updates 
a value in the list.

## Code Example

You'll have to check out my blog post, it's the only time I used this and it's the only documentation or example I have of this type of
setup. That is up at: https://gregbesso.wordpress.com/sharepoint/javascript-api-readwrite/

## Motivation

I was making a custom list to keep track of real estate listings and wanted to make a view that ranked them based on personal preferences 
and features. I hit a dead end and didn't want to give up, so that's why I made this little project. It's nothing special, but it did the trick.


## Installation

This is just a handful of text files that let you use JavaScript to interact with a SharePoint list. Check my blog post for an instructions:
https://gregbesso.wordpress.com/sharepoint/javascript-api-readwrite/

I did save the updateWeights.txt, the MicrosoftAjax.js, the jQuery.js and even the SharePoint list STP files as features. Mostly that is just 
for my own reference. I think the only way to cleanly use this example is to just use the updateWeights.txt file, modify it as needed 
to match your own custom lists, and then map to the correctly downloaded and setup Ajax and jQuery files. 

## API Reference

No API here. <sounds of crickets>

## Tests

No testing info here. <sounds of crickets>

## Contributors

Just a solo script project by moi, Greg Besso. Hi there :-)

## License

Copyright (c) 2015 Greg Besso

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