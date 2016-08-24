---
layout: post
title: text-transform 
published: true
author_github: oscar
---



The `text-transform` CSS property  gives you the ability to change the case of the text.

This property can be used to change all letters uppercase, only the first word to uppercase or  change every letter to lowercase. This can save time and make your code look more uniform for someone reviewing it later. `text-transform` is probably most commonly used to make a certain text standout , there's just something about all caps that make a word look better. 


## Syntax

Let's take a look at the syntax:

```css
  text-transform: capitalize|uppercase|lowercase
```
The code above shows you how you would use this property in css with its different values. So Let's explain those values in the next section.

### Values

* _uppercase_ :<br>
	The uppercase value changes all letters to caps. 
<p data-height="154" data-theme-id="dark" data-slug-hash="oLAYor" data-default-tab="css,result" data-user="nopity" data-embed-version="2" data-preview="true" class="codepen">See the Pen <a href="http://codepen.io/nopity/pen/oLAYor/">text-transform</a> by oscar (<a href="http://codepen.io/nopity">@nopity</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

* _lowercase_ :<br>
	The lowercase value turns all letters to lowercase.
<p data-height="145" data-theme-id="dark" data-slug-hash="bZPBmV" data-default-tab="html,result" data-user="nopity" data-embed-version="2" data-preview="true" class="codepen">See the Pen <a href="http://codepen.io/nopity/pen/bZPBmV/">text-transform: lowercase</a> by oscar (<a href="http://codepen.io/nopity">@nopity</a>) on <a href="http://codepen.io">CodePen</a>.</p>
As you can see in the code above, even though the paragraph has capital letters the final output is all lowercase which makes it easy to change the the case with out touching the code too much.
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
	
* _capitalize_ :<br>
	This value does something similar like `uppercase` value with one key difference in that it only capitalizes the first letter of each word.
	
<p data-height="157" data-theme-id="dark" data-slug-hash="grNLEO" data-default-tab="css,result" data-user="nopity" data-embed-version="2" data-preview="true" class="codepen">See the Pen <a href="http://codepen.io/nopity/pen/grNLEO/">text-transform: capitalize</a> by oscar (<a href="http://codepen.io/nopity">@nopity</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
## Special Notes

The capital value behaves in a certain way when it comes to the text its trying to change.

For dates that are written in the format "February 4th, 2016" it won't change to "February 4Th, 2016", which makes sense for most applications.

It's also important to note that `capitalize` only turns the first letter capital and ignores the rest of the word. So **"gamE"** will change too **"GamE"**.

One last note before closing this article is that  the `capitalize` value will also change the first letter after double, single quotes or the first letter after a hyphen.


So we covered the most common uses of the text-transform CSS property and as you see its good to use to change text quickly. 
