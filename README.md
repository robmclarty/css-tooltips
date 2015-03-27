# CSS Tooltips

*Tooltips for your DOM elements done in pure CSS.*

## Demo

[http://robmclarty.github.io/css-tooltips](http://robmclarty.github.io/css-tooltips)

## Usage

Simply add the class `tooltip` to the desired element, along with a direction class
which should be one of `top`, `right`, `bottom`, or `left`. With these classes in
place, add an attribute to your element called `data-tooltip` and the value of that
attribute will be displayed as the content of your tooltip on hover.

You may also, optionally, include the `wrap` class to use multi-line tooltips (the
default is single-line).

## Example

````
<span class="tooltip left" data-tooltip="This is a single-line tooltip!">Some text</span>

<span class="tooltip wrap left" data-tooltip="This is a multi-line tooltip!">Some text</span>
````

## Caveats

I chose to use generic class names for direction which may or may not already be
in use in your page. They are all relative to the `tooltip` class, but just be 
aware of any conflicts that might happen. It's easy to just change the direction 
class names to something else if needed ;)

## Author

Rob McLarty  
[http://twitter.com/robmclarty](@robmclarty)  
[http://robmclarty.com](//robmclarty.com)
