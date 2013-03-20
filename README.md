# Intro.js

> Better introductions for websites and features with a step-by-step guide for your projects.


## How to use
Intro.js can be added to your site in three simple steps:

**1)** Include `intro.js` and `introjs.css` (or the minified version for production) in your page.

**2)** Add `data-intro` and `data-step` to your HTML elements.  

For example: 

```html
<a href='http://google.com/' data-intro='Hello step one!' data-step='1'></a>
````
  
**3)** Call this JavaScript function:
```javascript
introJs().start();
````
 
Optionally, pass one parameter to `introJs` function to limit the presentation section.

**For example** `introJs(".introduction-farm").start();` runs the introduction only for elements with `class='introduction-farm'`.

<p align="center"><img src="http://usablica.github.com/intro.js/img/introjs-demo.png"></p>  


## Using with:

### Rails
If you are using the rails asset pipeline you can use the [introjs-rails](https://github.com/heelhook/intro.js-rails) gem.

### Yii framework
You can simply use this project for Yii framework: https://github.com/moein7tl/Yii-IntroJS

## Roadmap
- More browser compatibility


## Release History
 * **v0.2.0** - 2013-03-20
   - Ability to define tooltip position with `data-position` attribute
   - Add `onexit` and `oncomplete` callback
   - Better scrolling functionality
   - Redesign navigating buttons + add previous button
   - Fix overlay layer bug in wide monitors
   - Fix show element for elements with position `absolute` or `relative`
   - Add `enter` key for navigating in steps
   - Code refactoring
  
  
 * **v0.1.0** - 2013-03-16 
   - First commit. 

## Author
**Afshin Mehrabani**

- [Twitter](https://twitter.com/afshinmeh)
- [Github](https://github.com/afshinm)
- [Personal page](http://afshinm.name/)  

[Other contributors](https://github.com/usablica/intro.js/graphs/contributors)


## Support/Discussion
- [Google Group](https://groups.google.com/d/forum/introjs)


## License
> Copyright (C) 2012 Afshin Mehrabani (afshin.meh@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated 
documentation files (the "Software"), to deal in the Software without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, 
and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions 
of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED 
TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL 
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS 
IN THE SOFTWARE.
