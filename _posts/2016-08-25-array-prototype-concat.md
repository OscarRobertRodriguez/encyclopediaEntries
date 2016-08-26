---
layout: post
title: Array.prototype.concat
published: true
author_github: oscar
---


Array.prototype.concat() is a function that takes an array and combines it with another array or value/s giving the output of a new combined array.

I know this function looks weird and your probably wondering what that prototype word does so let's clear that up. You will see the prototype word also in other functions that come with JavaScript. This means that you don't have to set them up, they are already in JavaScript by default. Also unless you know what your doing it's best not to mess with these default functions.  

Think of prototype as a global class that affects everything of what it is attached to, no matter were it is in the code. So in this instance the "Array" in `Array.prototype.concat` refers to any Array object that you put in your script.

So when you see __"Array.protoype"__ you can take it to mean __"Insert any array. i'll make you global"__ for that function to do its job in this case, concat.

Now the last part - concat() - tells the array to combine with the array you mention at first with the array you put in-between the parenthesis which would be called the parameter. The concat method can receive more than one parameter, will get into that later. 

So we can translate the whole function from _**Array.prototype.concat()**_ in plain english to _**"Insert your Array. I'll make you global. I'll put us together and output a single array with all of us together"**_. That's a mouth full.   

Let's get into the syntax so we see how to actually use this with an array.


## Syntax



```javascript
var new_array = old_array.concat(value1[, value2[,[, valueN])
```

As you can see above you would assign a variable to hold the output of the concat method. It doesn't have to be done this way but is usually is the best way in most situations. 

You don't have to type prototype also since that's been setup already, you would put your name of your array instead. Above we call our array : _old_array_ and connect it with the concat method, which will take other arrays, numerical values or strings as arguments.


### Parameters

* **valueN**
    
    This is the parameter that is taken by the concat method. It can only accept strings, arrays which can be taken as a variable, an another array or as numbers. These values can be combined as long a separated by comma. 
    
    It can take multiple parameters there is no limit and the order the parameters are added are the same order you input them in the concat method.
    
    
    
Let's show you some examples now so these concepts can really sink in.
    
    

## Example 1

Here's an example of combining two arrays together and putting the output into another variable which we write to the document.

<p data-height="182" data-theme-id="dark" data-slug-hash="WxqPpZ" data-default-tab="js,result" data-user="nopity" data-embed-version="2" data-preview="true" class="codepen">See the Pen <a href="http://codepen.io/nopity/pen/WxqPpZ/">2 Array together</a> by oscar (<a href="http://codepen.io/nopity">@nopity</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Pretty simple.

## Example 2


<p data-height="216" data-theme-id="dark" data-slug-hash="JKQxGJ" data-default-tab="js,result" data-user="nopity" data-embed-version="2" data-preview="true" class="codepen">See the Pen <a href="http://codepen.io/nopity/pen/JKQxGJ/">More than 2 Arrays</a> by oscar (<a href="http://codepen.io/nopity">@nopity</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

This is pretty much the same as the first example but we have multiple arrays. We just input them to concat with commas and they all print out together.

## Example 3 - Complex

Now this one is a bit tricky but what we're doing is using concat twice. We concat are first array with a bunch of numbers and also arrays that contain numbers. Then we concat that output with the `names` variable to get the final output to the document.

<p data-height="233" data-theme-id="dark" data-slug-hash="dXBazZ" data-default-tab="js,result" data-user="nopity" data-embed-version="2" data-preview="true" class="codepen">See the Pen <a href="http://codepen.io/nopity/pen/dXBazZ/">concat once then twice</a> by oscar (<a href="http://codepen.io/nopity">@nopity</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

## Special Notes

There is one important note to mention. Arrays/values that you concat are a separate copy and do not affect the original values. 

That's all for today I hope that this made it clear on what Array.prototype.concat() does. 
