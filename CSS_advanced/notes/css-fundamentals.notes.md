# concept: css fundamentals
## resources
[css first steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps)\
[css validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

## overview 
cascading style sheets work by 
1. selecting and html element
2. choosing the property to alter
3. applyinig a certain value

### syntax
```css
element-selector {
	style-property-a: value;
	style-property-b: value;
	style-property-c: value;
}
```

each property-value pair is known as a declaration\
each declaration ought to go an a separate line

## applying css to html
### external stylesheet
in this case all css code is kept in a separate `.css` file\
this is the most common method\
an advantage here is that a single css style can be applied to multiple webpages

### internal stylesheet
here, the stylesheet resides within the html file\
the css code would be placed within the `<style>` elment in `<head>`

### inline styles
these are css declarations set in the `style` attribute of the html element for which they're meant to affect\
example:`<h1 style="color: deepskyblue; text-align: center;">Hello, World!</h1>`\
these always take precedence over any stylesheet

## invalid css
if a browser encounters a css selector, property, or value that it doesn't recognize or understand, it will ignore the rule/s in question and move on to the next. for this, always validate your css.

a browser's developer tools can also highlight invalid properties and values

