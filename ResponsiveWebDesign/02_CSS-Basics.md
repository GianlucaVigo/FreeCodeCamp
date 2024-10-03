# Learn Basic CSS by Building a Cafe Menu

## Style Element
Defined within the <head> element.

\<style> *content* \</style>

You can add style to an element considering the following sintax:

element1, element2, ... {

  property: value;
  
}

OR

\#id1 {

property: value;

}

For instance: h1 {text-align: center}.

## External CSS Style file
There's no need to put the <style> tags. It can be referenced by means of the link element.

## Link [VOID ELEMENT]
Defined in the <head> element.

Attributes:
- rel: specify the type of linked document (ex. stylesheet, ...)
- href: specify the address of the resource (ex. styles.css)

## Div
It's used mainly for design layout purposes.

## CSS comment
/* *comment* */

## Class selector
It's common to use different selectors to style elements.

.class-name{

*styles*

}

OR

.class-name ELEMENT{

*styles*

}


Instead of id, use class attribute.

## Article
Contains multiple elements that have related information. (ex. p elements)

\<article> *content* \</article>

# CSS Properties

Properties:
- width (in px or %)
- background-color
- text-align (center, rigth, left)
- margin-LOCATION, LOCATION:{left, right, top, bottom} (in px)
- background-image (url(https://URL))
- display (inline block)
- padding-LOCATION, LOCATION:{left, right, top, bottom} (in px)
- max-width (in px)
- padding (in px)
- font-family (sans-serif, Impact, ...)
- font-style (italic, ...)
- font-size
- height (for hr element, ...)
- border-color (for hr element, ...)
